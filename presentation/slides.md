---
theme: seriph
background: none
highlighter: shiki
lineNumbers: true
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
<h1>About me</h1>

TBD

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
  <li>Opinionated code formatter</li>
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
  <li>Forces best practices</li>
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
  <li>Superset of JS</li>
  <li v-click>Forces strict types</li>
  <li v-click>Improves code hinting</li>
</ul>

---
layout: center
class: 'text-center'
info: IDE 1
---

<div style="display: flex; gap: 4vw;">
  <img src="/assets/vscode.svg" style="width: 8vw; height: auto;">
  <img src="/assets/phpstorm.svg" style="width: 8vw; height: auto;">
  <img src="/assets/webstorm.svg" style="width: 8vw; height: auto;">
  <span style="font-size: 8vw;">…</span>
</div>

---
layout: two-cols
info: IDE 2
---

<div class="center-horizontal center-vertical" style="gap: 3vh;">
  <img src="/assets/vscode.svg" style="width: 5vw; height: auto;">
  <img src="/assets/phpstorm.svg" style="width: 5vw; height: auto;">
  <img src="/assets/webstorm.svg" style="width: 5vw; height: auto;">
</div>

::right::

<ul class="center-vertical">
  <li>Autocompletion</li>
  <li v-click>Auto formatting</li>
  <li v-click>Type hints</li>
  <li v-click>Code hints</li>
  <li v-click>Go to definition/usage</li>
  <li v-click>Spell checking</li>
</ul>

---
layout: center
info: Fight
---

<h1>How to fight against enemies?</h1>
<img src="https://media.giphy.com/media/WwC5VAvhHoH7EjCpPz/giphy.gif">

---
layout: center
info: Fight
---

<h1>How to fight against enemies?</h1>
<ul class="center-vertical">
  <li>Ignore setup instructions</li>
  <li v-click>Skip git hooks</li>
  <li v-click>Ignore pipelines</li>
  <li v-click>Fight opinions</li>
  <li v-click>Use your own setup</li>
</ul>

---
layout: center
class: 'text-center'
info: Weapons
---

<h1>Hackers: choose your weapons!</h1>
<img src="https://media.giphy.com/media/1eEv7v51FEI3L54jpr/giphy.gif">

---
layout: center
info: Weapons
---

```js
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The to be filtered array.
 * @param {function} callback - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(sourceArray, callback) {
  const result = [];

  for (let index = 0; index < sourceArray.length; index += 1) {
    const value = sourceArray[index];

    if (callback(value, index, sourceArray)) {
      result.push(value);
    }
  }

  return result;
}
```

---
layout: two-cols
info: Naming 1.1
---

<h1>Naming</h1>

<div class="center-vertical" style="padding-right: 4vw;">
  <h2>Use single letters, symbols, emojis or accented letters</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  a, b, c, 🍬, 𝘼, 𝟙. í, ä
  ```
</div>

::right::

```js {all|12-15}
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The to be filtered array.
 * @param {function} callback - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(sourceArray, callback) {
  const result = [];

  for (let index = 0; index < sourceArray.length; index += 1) {
    const value = sourceArray[index];

    if (callback(value, index, sourceArray)) {
      result.push(value);
    }
  }

  return result;
}
```

<!--
Note: Depending on your language some of these options are not valid. But you can still use them in your comments!
-->

---
layout: two-cols
info: Naming 1.2
---

<h1>Naming</h1>

<div class="center-vertical" style="padding-right: 4vw;">
  <h2>Use single letters, symbols, emojis or accented letters</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  a, b, c, 🍬, 𝘼, 𝟙. í, ä
  ```
</div>

::right::

```js {12-15}
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The to be filtered array.
 * @param {function} callback - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(sourceArray, callback) {
  const result = [];

  for (let i = 0; i < sourceArray.length; i += 1) {
    const value = sourceArray[i];

    if (callback(value, i, sourceArray)) {
      result.push(value);
    }
  }

  return result;
}
```

---
layout: two-cols
info: Naming 2.1
---

<h1>Naming</h1>

<div v-click-hide class="center-vertical" style="padding-right: 4vw;">
  <h2>Use single letters, symbols, emojis or accented letters</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  a, b, c, 🍬, 𝘼, 𝟙. í, ä
  ```
</div>

<div v-after class="center-vertical" style="padding-right: 4vw;">
  <h2>Use abbreviation and A.C.R.O.N.Y.M.S.</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  col, fn, gt, arg, obj, 
  opts, conf, imo, bg, chk, ge
  ```
</div>



::right::

```js {12-15|10,16,20}
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The to be filtered array.
 * @param {function} callback - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(sourceArray, callback) {
  const result = [];

  for (let ì = 0; ì < sourceArray.length; ì += 1) {
    const value = sourceArray[ì];

    if (callback(value, ì, sourceArray)) {
      result.push(value);
    }
  }

  return result;
}
```

---
layout: two-cols
info: Naming 2.2
---

<h1>Naming</h1>

<div v-click-hide class="center-vertical" style="padding-right: 4vw;">
  <h2>Use abbreviation and A.C.R.O.N.Y.M.S.</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  col, fn, gt, arg, obj,
  opts, conf, imo, bg, chk, ge
  ```
</div>

<div v-after class="center-vertical" style="padding-right: 4vw;">
  <h2>Use foreign, made up or lesser known, alternative words with the same meaning</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reprezenti, opcioj, werte,
  grid, expense, humptyDumpty
  ```
</div>

::right::


```js {10,16,20|4,5,9,12-15}
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The to be filtered array.
 * @param {function} callback - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(sourceArray, callback) {
  const res = [];

  for (let ì = 0; ì < sourceArray.length; ì += 1) {
    const value = sourceArray[ì];

    if (callback(value, ì, sourceArray)) {
      res.push(value);
    }
  }

  return res;
}
```

---
layout: two-cols
info: Naming 3.1
---

<h1>Naming</h1>

<div v-click-hide class="center-vertical" style="padding-right: 4vw;">
  <h2>Use foreign, made up or lesser known, alternative words with the same meaning</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reprezenti, opcioj,
  grid, expense, humptyDumpty
  ```
</div>

<div v-after class="center-vertical" style="padding-right: 4vw;">
  <h2>Misspell everything</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reandom, eveerything, everyting, evrything, 
  vaule, vlaue, vale
  ```
</div>

::right::

```js {4,5,9,12-15|13,15,16}
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The to be filtered array.
 * @param {function} thanos - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(lischtä, thanos) {
  const res = [];

  for (let ì = 0; ì < lischtä.length; ì += 1) {
    const value = lischtä[ì];

    if (thanos(value, ì, lischtä)) {
      res.push(value);
    }
  }

  return res;
}
```

---
layout: two-cols
info: Naming 4.1
---

<h1>Naming</h1>

<div v-click-hide class="center-vertical" style="padding-right: 4vw;">
  <h2>Misspell everything</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reandom, eveerything, everyting, evrything, 
  vaule, vlaue, vale
  ```
</div>

<div v-after class="center-vertical" style="padding-right: 4vw;">
  <h2>Use random capitalization or formats</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  comPutdyNamIcValuE, get_distance_from_la, 
  calculate-distance-to-moon, valueA, valuea
  ```
</div>

::right::


```js {13,15,16|9}
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The to be filtered array.
 * @param {function} thanos - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(lischtä, thanos) {
  const res = [];

  for (let ì = 0; ì < lischtä.length; ì += 1) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      res.push(vaule);
    }
  }

  return res;
}
```
---
layout: two-cols
info: Naming 4.1
---

<h1>Naming</h1>

<div class="center-vertical" style="padding-right: 4vw;">
  <h2>Use random capitalization or formats</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  comPutdyNamIcValuE, get_distance_from_la, 
  calculate-distance-to-moon, valueA, valuea
  ```
</div>

::right::


```js {9}
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The to be filtered array.
 * @param {function} thanos - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const res = [];

  for (let ì = 0; ì < lischtä.length; ì += 1) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      res.push(vaule);
    }
  }

  return res;
}
```
---
layout: two-cols
info: Naming 4.1
---

<div style="padding-right: 0.5vw;">

```js
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The to be filtered array.
 * @param {function} callback - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filter(sourceArray, callback) {
  const result = [];

  for (let index = 0; index < sourceArray.length; index += 1) {
    const value = sourceArray[index];

    if (callback(value, index, sourceArray)) {
      result.push(value);
    }
  }

  return result;
}
```

</div>

::right::


```js
/**
 * Filters an array, by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The to be filtered array.
 * @param {function} thanos - Condition callback that is called for each entry.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const res = [];

  for (let ì = 0; ì < lischtä.length; ì += 1) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      res.push(vaule);
    }
  }

  return res;
}
```


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
