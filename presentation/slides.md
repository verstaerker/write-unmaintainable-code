---
theme: seriph
background: none
highlighter: shiki
lineNumbers: false
layout: center
---

#
<img src="/assets/title.png" style="width: 80%; height: auto; display: block; margin: auto;">

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: center
class: 'text-center'
---

# Your worst enemies

<img src="/assets/copyrighted/thanos.jpg" style="width: 80%; height: auto; display: block; margin: auto;">

---
layout: center
class: 'text-center'
info: Prettier 1
---

<img src="/assets/prettier.svg">

---
layout: two-cols
info: Prettier 2
---

<div class="center-horizontal center-vertical">
  <img src="/assets/prettier2.svg" style="width: 9vw; height: auto;">
</div>

::right::

<ul class="center-vertical">
  <li v-click>Opinionated code formatter</li>
  <li v-click>Automated code styles</li>
  <li v-click>Supports Git Hooks</li>
  <li v-click>Supports CI</li>
</ul>

---
layout: center
class: 'text-center'
info: ESLint 1
---

<img src="/assets/eslint.svg" style="width: 25vw; height: auto;">

---
layout: two-cols
info: ESLint 2
---

<div class="center-horizontal center-vertical">
  <img src="/assets/eslint2.svg" style="width: 8vw; height: auto;">
</div>

::right::

<ul class="center-vertical">
  <li v-click>Forces best practices</li>
  <li v-click>Forces code styles</li>
  <li v-click>Supports `--fix`</li>
  <li v-click>Supports Git Hooks</li>
  <li v-click>Supports CI</li>
</ul>

---
layout: center
class: 'text-center'
info: TypeScript 1
---

<img src="/assets/typescript.svg" style="width: 10vw; height: auto;">

---
layout: two-cols
info: TypeScript 2
---

<div class="center-horizontal center-vertical">
  <img src="/assets/typescript.svg" style="width: 8vw; height: auto;">
</div>

::right::

<ul class="center-vertical">
  <li v-click>Superset of JS</li>
  <li v-click>Forces strict types</li>
  <li v-click>Improves code hinting</li>
</ul>

---
layout: center
class: 'text-center'
info: TypeScript 1
---

<div style="display: flex; gap: 4vw;">
  <img src="/assets/vscode.svg" style="width: 8vw; height: auto;">
  <img src="/assets/phpstorm.svg" style="width: 8vw; height: auto;">
  <img src="/assets/webstorm.svg" style="width: 8vw; height: auto;">
  <span style="font-size: 8vw;">…</span>
</div>

---
layout: two-cols
info: TypeScript 2
---

<div class="center-horizontal center-vertical" style="gap: 3vh;">
  <img src="/assets/vscode.svg" style="width: 5vw; height: auto;">
  <img src="/assets/phpstorm.svg" style="width: 5vw; height: auto;">
  <img src="/assets/webstorm.svg" style="width: 5vw; height: auto;">
</div>

::right::

<ul class="center-vertical">
  <li v-click>Autocompletion</li>
  <li v-click>Go to definition/usage</li>
  <li v-click>Auto formatting</li>
  <li v-click>Type hints</li>
  <li v-click>Code hints</li>
  <li v-click>Spell checking</li>
</ul>

---

# Code

Use code snippets and get the highlighting directly![^1]

```vue {all|2|1-6|9|all}
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: User) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

[^1]: [Learn More](https://sli.dev/guide/syntax.html#line-highlighting)

<style>
.footnotes-sep {
  @apply mt-20 opacity-10;
}
.footnotes {
  @apply text-sm opacity-75;
}
.footnote-backref {
  display: none;
}
</style>

---

# Components

<div grid="~ cols-2 gap-4">
<div>

```vue
function convertDegreeToRadius(degreeValue) {
  return degreeValue * Math.PI / 180;
}
```

</div>
<div>

Text Neben Code

</div>
</div>
<div grid="~ cols-2 gap-4">
<div>

```vue
function convertDegreeToRadius(degreeValue) {
  return degreeValue * Math.PI / 180;
}
```

</div>
<div>

```vue
function shp_of_wheel(c) {
  const calculations = Math;

  return c * calculations.PI / (0.5 * 360);
}
```

</div>
</div>

---

# Live Coding

```js {monaco}
function shp_of_wheel(c) {
  const calculations = Math;

  return c * calculations.PI / (0.5 * 360);
}
```
