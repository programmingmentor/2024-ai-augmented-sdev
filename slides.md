---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: AI-Augmented розробка програмних проєктів
info: |
  ## Виступ на конференції IF IT FORUM 2024

# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# AI-Augmented розробка програмних проєктів

В'ячеслав Колдовський, SoftServe

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="m-6 flex gap-2 fixed bottom-0 right-0 flex-col items-end">
  <a href="https://www.youtube.com/c/programmingmentorua">
    <div class="h-8 w-8">
      <img src="/pm-logo.jpg" class="h-full w-full rounded-full"/>
    </div>
  </a>
  <a href="https://career.softserveinc.com/uk-ua/softserve-academy">
    <div class="h-12 w-24">
      <img src="/ssa-logo-white.svg" class="h-full w-full"/>
    </div>
  </a>
</div>

<style>
  a {
    text-decoration: none;
    border: 2.4px solid transparent;
  }
  a:hover {
    border-color: var(--slidev-theme-primary);
  }
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-left
image: /vyacheslav-koldovskyy.png
---

# В'ячеслав Колдовський

- Ph.D, доцент
- 20+ років в IT
- SoftServe Academy Competence Manager
- Certified Google Cloud Professional Architect
- Ентузіаст Практичного AI
- Ютубер: [youtube.com/@programmingmentorua](https://www.youtube.com/@programmingmentorua)
- Блогер: [t.me/programmingmentor](https://t.me/programmingmentor)
- Лінкедін: [koldovsky](https://www.linkedin.com/in/koldovsky/)

---
layout: image-left
image: /software-engineer-1-0.jpg
---

# Software Engineer 1.0

- Знання: книжки, статті, паперова документація
- Комуникація через email, телефон
- Примітивні інструменти розробника, системи контролю версій
- SDLC: Waterfall, V-model
  <br>
  <br>
  <v-click>Якою була швидкість розробки?</v-click>
  <br>
  <v-click>Чи були це менш кваліфіковані фахівці, ніж сьогодні?</v-click>

---
layout: image-left
image: /software-engineer-2-0.webp
---

# Software Engineer 2.0

- Знання: Інернет, онлайн-курси, Google, StackOverflow
- Комуникація через Slack, Teams, Discord, Zoom, Google Meet, Telegram
- Продвинуті інструменти розробника, системи контролю версій з CI/CD
- SDLC: Agile, DevOps
  <br>
  <br>
  <v-click>Яка швидкість розробки?</v-click>
  <br>
  <v-click>Наскільки більш кваліфіковані в порівнянні з 1.0?</v-click>

<!--
Nasa Programmer Margret Hamilton standing next to the code that brought man to the moon.
-->

---

# Software Engineer 3.0

<div class="absolute inset-0 flex justify-center items-center">
  <div class="text-9xl font-bold">?</div>
</div>

---
layout: image
image: /timeline-of-tech-longterm.png
backgroundSize: contain
title: Timeline of Tech
---

---
layout: image
image: /timeline-of-tech-2000.png
backgroundSize: contain
title: Timeline of Tech 2000
---

---
layout: center
---

# Це не зараз все швидко розвивається, це раніше все відбувалося повільно

<div class="flex justify-center">
  <Tweet class="w-1/2" id="1848558163756519607" />
</div>

---
layout: center
---

# Чи є в нас в галузі проблеми взагалі?

---

# Неповний перелік проблем в IT

- Недосконалість технологій, інструментів, платформ
- Варіантивність архітектурних рішень, технологій, платформ
- Стабільними є лише постійні зміни технологій
- Технічний борг
- Кіберзагрози
- Регуляції, стандарти, комплаєнси
- Інтернаціоналізація
- Інертність адаптації до зміни вимог
- Складність рішень
- Дороговизна
- Повільність
- Недостатньо кваліфікованих фахівців
- Складно давати імена сутностям :)

---
layout: center
---

# В чому основна проблема IT?

<v-click>
  Людський фактор
</v-click>

---
layout: center
---

# Що таке програмний код?

<v-click>
  Це думка розробника, записана мовою, яка зрозуміла йому та комп'ютеру
</v-click>

---
layout: center
---

# Коли були створені концепції мов програмування, якими ми користуємося сьогодні?

<v-click>
- 1957 - Fortran
<br>
- 1958 - Lisp
<br>
- 1959 - COBOL
</v-click>

---
layout: image
image: /plangs-geneaological-tree.gif
title: Генеалогічне дерево мов програмування
backgroundSize: contain
---

---

# Що таке програмна інженерія?

- Мистецтво
- Наука
- Ремесло

---
layout: image
image: /art-science-craft-01.gif
title: Art, Science, Craft
---

---
layout: image
image: /art-science-craft-02.gif
title: Art, Science, Craft - Щось одне
---

---

# Чому ремесло?

- Алгоритми
- Структури даних
- Парадигми програмування
- Архітектури програмних систем
- Патерни, принципи, практики
- Мови, бібліотеки, фреймворки
- Інструменти, системи контролю версій, CI/CD
- ОС, мережі, контейнери, хмарні платформи

---
layout: center
---

# Основна ідея: не треба креативити чи винаходити нові знання, треба вивчити і застосовувати те, що вже було винайдено

---
layout: center
---

# З якою роботою AI справляється найкраще?

---
layout: center
---

# Епоха AI в програмній інженерії

---
layout: image
image: /ai-adoption-0-100.png
backgroundSize: contain
---

# Де ми зараз?

<style>
  h1 {
    color: black;
  }
  .slidev-layout {
    background-color: white;
  }
</style>

---
layout: image
image: /ai-adoption-0-100-detailed.png
backgroundSize: contain
---

# А якщо розбити на етапи?

<style>
  h1 {
    color: black;
  }
  .slidev-layout {
    background-color: white;
  }
</style>

---
layout: center
---

# LLM is the king

---
layout: image
image: /chatbot-arena-overall.png
backgroundSize: contain
title: Chatbot Arena Overall
---

---
layout: image
image: /chatbot-arena-coding.png
backgroundSize: contain
title: Chatbot Arena Coding
---

---
layout: center
---

# Яке місце LLM в SDLC?

---
layout: image
image: /sdlc.png
backgroundSize: contain
title: SDLC
---

---
layout: center
---

# Що ми робимо на етапі аналізу вимог і проєктування?

<v-click>
  Документи, діаграми і т.д. і т.п.
</v-click>

---
layout: image
image: /diagram-mermeid.gif
backgroundSize: contain
title: Mermeid
---

---
layout: center
---

# Що з етапом імплементації?

---
layout: image
image: /gh-copilot.png
backgroundSize: contain
title: GitHub Copilot
---

---
layout: image
image: /gh-copilot-error.png
backgroundSize: contain
title: GitHub Copilot Error
---

---
layout: image
image: /gh-copilot-public-code.png
backgroundSize: contain
title: GitHub Copilot Public Code
---

---
layout: image
image: /copilot-in-github.gif
backgroundSize: contain
title: Copilot in GitHub
---

---
layout: image
image: /ms-ai-improves-ai.gif
backgroundSize: contain
title: MS Copilot Optimization
---

---
layout: image
image: /cursor-ide.png
backgroundSize: contain
title: Cursor IDE
---

---
layout: center
---

# Переваги Cursor IDE

<v-clicks>

- Вбудований AI-асистент на базі GPT-4
- Генерація коду та рефакторинг за допомогою AI
- Інтелектуальне автодоповнення коду
- Пояснення та документування коду
- Швидкий пошук та навігація по кодовій базі
- Інтеграція з популярними системами контролю версій
- Підтримка багатьох мов програмування
- Безкоштовний для особистого використання

</v-clicks>

---
layout: image
image: /cursor-ide-codegen.gif
backgroundSize: contain
title: Cursor IDE Code Generation
---

---
layout: center
---

# А як зробити красиво?

---
layout: image
image: /v0-dev.gif
backgroundSize: contain
title: v0.dev
---

<!--
https://v0.dev/chat/90t1YNyiuqQ?b=b_tECxpRUgJb8
-->

---
layout: center
---

# Хто любить Code Reviews?

<v-click>
  CodeRabbit
</v-click>

---
layout: image
image: /coderabbit.gif
backgroundSize: contain
title: CodeRabbit
---

---
layout: center
---

# Хто любить писати тести?

<v-click>
  AI
</v-click>

---
layout: center
---

# Агенти

---
layout: image
image: /matrix-agents.png
backgroundSize: contain
title: Matrix Agents
---

---
layout: image
image: /software-agents.png
backgroundSize: contain
title: Software Agents with Rivet
---

---
layout: image
image: /openai-swarm.png
backgroundSize: contain
title: OpenAI Swarm
---

---
layout: image
image: /anthropic-computer-use.png
backgroundSize: contain
title: Anthropic Computer Use
---

---
layout: center
---

# SWE Bench

---
layout: image
image: /swe-bench.png
backgroundSize: contain
title: SWE Bench
---

---
layout: image
image: /bolt.new.gif
backgroundSize: contain
title: Bolt.new
---

---
layout: center
---

# Ефект чорного лебедя

---
layout: image
image: /no-game-engine.png
backgroundSize: contain
title: No Game Engine
---

---
layout: center
---

# Assisted vs Augmented

<div class="grid grid-cols-2 gap-4">
  <div>
    <h2 class="text-2xl font-bold mb-4">AI Assisted</h2>
    <ul class="list-disc list-inside">
      <li>AI як інструмент підтримки</li>
      <li>Розробник контролює процес</li>
      <li>AI генерує код за запитом</li>
      <li>Обмежена автономність AI</li>
      <li>Фокус на окремих завданнях</li>
    </ul>
  </div>
  <div>
    <h2 class="text-2xl font-bold mb-4">AI Augmented</h2>
    <ul class="list-disc list-inside">
      <li>AI як активний партнер</li>
      <li>Співпраця людини та AI</li>
      <li>AI пропонує рішення проактивно</li>
      <li>Висока автономність AI</li>
      <li>Комплексний підхід до розробки</li>
    </ul>
  </div>
</div>

---

# Software Engineer 3.0

<div class="absolute inset-0 flex justify-center items-center">
  <div class="text-8xl font-bold">AI-Augmented SWE</div>
</div>

---
layout: image
image: /ai-adoption-0-100-detailed.png
backgroundSize: contain
---

# То де ми зараз?

<style>
h1 {
  color: black;
}
.slidev-layout {
  background-color: white;
}
</style>

<v-click>
  <div
      v-motion
      :initial="{ y: 260, x: -450, opacity: 1 }"
      :enter="{ y: 0, x: 0, opacity: 1, transition: { delay: 0, duration: 30000 } }"
      class="absolute top-[110px] left-3/5 transform -translate-x-1/2">
    <div class="text-6xl text-red-500">↓</div>
  </div>
</v-click>

---
layout: end
---

# Дякую за увагу!

<div class="flex justify-center w-full h-30 items-center">
  <img src="/slides-qr.png" class="w-25 h-25"/>
</div>
