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
Guten Abend alle zusammen

Schön das ihr hier zur valantic gefunden habt.
-->

---
layout: image-left
image: /assets/patric.jpg
---

<picture style="display: block; margin-bottom: 3vh;">
 <source media="prefers-color-scheme: dark" src="/assets/logo-valantic-white.svg">
 <source media="prefers-color-scheme: light" src="/assets/logo-valantic.svg">
 <img style="width: 5vw; height: auto;" src="/assets/logo-valantic-white.svg">
</picture>
<h1>Patric Eberle</h1>

Senior Frontend Developer and Teamlead



<ul style="display: flex; align-items:center; list-style: none; padding: 0; margin: 12vh 0 0 0; gap: 1vw;">
  <li style="margin: 0; padding: 0;">🎲</li>
  <li style="margin: 0; padding: 0;">👩🏽‍❤️‍👨🏻</li>
  <li style="margin: 0; padding: 0;">
    <img src="/assets/netflix.svg" style="width: 1em; height: auto">
  </li>
  <li style="margin: 0; padding: 0;">🏃🏻‍♂️</li>
  <li style="margin: 0; padding: 0;">🧘🏻‍♂️</li>
  <li style="margin: 0; padding: 0;">
    <img src="/assets/vue.svg" style="width: 1em; height: auto">
  </li>
</ul>

<ul style="list-style: none; padding: 0; margin: 4vh 0 0 0; gap: 1vw; font-size: 0.8em;">
  <li style="margin: 0; padding: 0 0 1vh 0;">
    <a class="hidden-link" href="https://github.com/patric-eberle">https://github.com/patric-eberle</a>
  </li>
  <li style="margin: 0; padding: 0 0 1vh 0;">
    <a class="hidden-link" href="https://www.linkedin.com/in/patric-eberle-22518911a">https://www.linkedin.com/in/patric-eberle-22518911a</a>
  </li>
  <li style="margin: 0; padding: 0 0 1vh 0;">
    <a class="hidden-link" href="mailto:patric.eberle@cec.valantic.com">patric.eberle@cec.valantic.com</a>
  </li>
</ul>

<!--
Mein Name ist Patric Eberle

Ich bin
- **Senior Frontend Developer**
- **Lead** von einem 5 Köpfigen Frontendteam beim Valantic
- **seit 2016** bei valantic

In meiner Freizeit
- mit Freunden für einen **Strategiespieleabend** treffen
- Geniesse ich die Zeit mit meiner **Partnerin**
- Verbringe ich zu viel Zeit auf **Netflix**
- **Laufe** ich gerne
- habe ich **Yoga** entdeckt
- bin ich **Vue Enthusiast**

Meine **Kontaktmöglichkeiten** verraten es schon:
Ich **bin kein sozialer Mensch**.

Danken möchte ich auch **Mathias Ober**,
der mich nicht nur bei der Umsetzung,

sondern **in der Vergangenheit** auch mit
**diversen inspierierenden Beispielen** unterstütz hat.

**Ah Mist** ... dass wollten wir ja gar nicht erwähnen 😬
-->

---
layout: center
---

#
<img src="/assets/title.png" style="width: 80%; height: auto; display: block; margin: auto;">

<!--
In meinem Talk geht es um das Thema
welche Praktiken ihr anwenden könnt,

um euch **als Entwickler
unentbehrlich zu machen**.

Sprich, wie schreibt man Code,
den im **Optimalfall nur ihr versteht**.
-->

---
layout: center
class: text-center
---

# Your worst enemies

<img src="/assets/copyrighted/thanos.jpg" style="width: 80%; height: auto; display: block; margin: auto;">

<!--
**Bevor** wir aber **einsteigen**

müssen wir uns mit **unseren Gegenspielern**
vertraut machen, die sich **für ein 
geordnetes Universum** einsetzen

uns aber **beim Schreiben** unseres
**professionellen Codes in die Quere**
kommen könnten.
-->

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

<!--
Prettier ist

- **rechthaberischer** Code Formatierer<br>
*Kein Mitspracherecht, etwas für Amateure*

- **Automatisiert** das anwenden von Codestyles<br>
*Kontrollverlust über eigenen Code*

- Kann in **Git Hooks** ausgeführt werden<br>
*Code wird einfach überschrieben*

- Kann in **Continious Integration Pipelines** ausgeführt werden<br>
*Vortlaufende Integration, Nicht angepasste Code führt zum Abbruch der Pipeline*
-->

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
  <li>Enforces best practices</li>
  <li v-click>Enforces code styles</li>
  <li v-click>Supports `--fix`</li>
  <li v-click>Supports Git Hooks</li>
  <li v-click>Supports CI</li>
</ul>

<!--
- **Zwingt** sogenannte **"Best Practices"** auf<br>
*Anfänger haben mitspracherecht*


- Setzt **Codestyle-Standards** durch<br>
*Meine Kreativität wird unterdrück, ich bin eingeschränkt*

- **Automatische Korrektur**<br>
*Kann von jedem Anfänger ausgeführt werden*

- Kann ebenfalls in den **Git Hooks und CI Pipelines** ausgeführt werden
-->

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
  <li v-click>Enforces strict types</li>
  <li v-click>Improves code hinting</li>
</ul>

<!--
- Ein **Superset von JS**<br>
*"Erweitert" JS mit Typisierung und einigen anderen Besonderheiten*

- *Erzwingt spezifische Typen*<br>
*Verhindert "ungültige" Typen und mehrfache Verwenden von Variablen*

- Unterstütz IDE beim Anzeigen von *Code-Hinweisen*<br>
*Selbst Unerfahren glauben, komplexe Software bedienen zu können, Code dokumentiert sich selbst*
-->

---
layout: center
class: 'text-center'
info: IDE 1
---

<div style="display: flex; gap: 2vw;">
  <img src="/assets/vscode.svg" style="width: 3vw; height: auto;">
  <img src="/assets/phpstorm.svg" style="width: 3vw; height: auto;">
  <img src="/assets/webstorm.svg" style="width: 3vw; height: auto;">
  <span style="font-size: 3vw;">…</span>
</div>

---
layout: two-cols
info: IDE 2
---

<div class="center-horizontal center-vertical" style="gap: 3vh;">
  <img src="/assets/vscode.svg" style="width: 6vh; height: auto;">
  <img src="/assets/phpstorm.svg" style="width: 6vh; height: auto;">
  <img src="/assets/webstorm.svg" style="width: 6vh; height: auto;">
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

<!--
IDEs

- **Vervollständigungshilfe**<br>
*Unterstützen unerfahrene Entwickler beim Ergänzen von bestehendem Code*

- **Code Formatierung**<br>
*Kann Detailarbeit innert Sekunden über den Haufen werfen*

- **Typen Informationen**<br>
*Versuchen automatisiert Informationen über den Code zu extrahieren*

- **Code Empfehlungen/Dokumentation**<br>
*Gibt Unerfahrenen Hintergrundinformationen zu unbekannten Eigenschaften*

- **Zu Definitionen und Verwendungen springen**<br>
*Erlaubt es Anfängern sich im Code zu bewegen als würden sie sich auskennen*

- **Rechtschreibprüfung**<br>
*Fügt störende, optische Elemente zum Code hinzu*
-->

---
layout: center
info: Fight
class: text-center
---

<h1>How to fight enemies?</h1>
<img src="https://media.giphy.com/media/WwC5VAvhHoH7EjCpPz/giphy.gif">

<!--
Was kannst du **gegen** diese **Abnormalitäten** unternehmen?
-->

---
layout: center
info: Fight
---

<h1>How to fight against enemies?</h1>
<ul class="center-vertical">
  <li>Ignore setup instructions</li>
  <li v-click>Skip Git Hooks</li>
  <li v-click>Ignore pipelines</li>
  <li v-click>Fight opinions</li>
  <li v-click>Use your own setup</li>
</ul>

<!--
- Ignoriere gezielt **Installationsinstruktionen**<br>
*Git Hooks, Scripts und Pipelines manipulieren*

- *Git Hooks* beim Commit *unterbinden*

- **Pipelines** beim Mergen **ignorieren**<br>
*Achte darauf, dass du Adminrechte zu Beginn des Projektes beantragst*

- Für **Diskussionen** mit Anfängern und Besserwissern **wapnen**<br>
*Suche stichfeste, nicht wiederlegbare Argumente für
Diskussionen, im Notfall ein Streitgespräch beginnen*

- Eigenes **Softwaresetup** verwenden<br>
*Dabei geziehlt Projektvorgaben und Best Practices ignorieren*
-->

---
layout: center
class: text-center
info: Weapons
---

<h1>Hackers: choose your weapons!</h1>
<img src="https://media.giphy.com/media/1eEv7v51FEI3L54jpr/giphy.gif">

<!--
Jetzt wird es **endlich Zeit einzutauchen**!
-->

---
layout: center
info: Weapons
---

```js
/**
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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
**Beispielcode**

Eine Array **Filtermethode**

Gibt es zwar **nativ**, aber es **immer gut eigene Methoden für generelle Prozesse** zu schreiben

- **Dokumentation**
- Erwartet **2 Variablen**
- Methode **iteriert** über Einträge
- Ruft für jeden Eintrag die **Callback** Funktion auf
- Gibt das **reduzierte Array zurück**
-->

---
layout: center
class: text-center
info: Weapons
---

<h1>Naming</h1>

<!--
Die **Basis, wie jeder professionelle Entwickler weiss**, ist die Benennung von Code Elementen.

Hier haben wir die **grösste, kreative Freiheit**.

Achte darauf, dass du **Code für**

- **dich**
- **Maschinen bzw. Browser**

die **Lesbarkeit für andere Entwickler bewusst ignorieren**!
-->

---
layout: two-cols
info: Naming 1.1
---

<h1>Naming</h1>

<div class="" style="padding-right: 2vw;">
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
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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
Achtung: basierend auf der verwendeten **Programmiersprache** sind einige der Empfehlungen **ggf. nicht anwendbar**.

- **Einzelne Buchstaben**
- **Symbole & Sonderzeichen**
- **Sonderzeichen, die 2 Tastendrücke benötigen**
- **Emojis**


Könnten **alles mit einzelnen Buchstaben** ersetzten.

Aus **Gründen der Nachvollziehbarkeit** beschränken wir uns auf "index"
-->

---
layout: two-cols
info: Naming 1.2
---

<h1>Naming</h1>

<div class="" style="padding-right: 2vw;">
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
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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

<div v-click-hide class="" style="padding-right: 2vw;">
  <h2>Use single letters, symbols, emojis or accented letters</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  a, b, c, 🍬, 𝘼, 𝟙. í, ä
  ```
</div>

<div v-after class="" style="padding-right: 2vw;">
  <h2>Use abbreviations and A.C.R.O.N.Y.M.S.</h2>
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
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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

<!--
Wir können einfach **i** verwenden.

Besser wäre ein **nicht verfolgbarer Buchstabe** z.B. **l**oop, **d**urchgang oder **v**ariable

Oder wir können einen **Akzent** verwenden

_

Auch **Abkürzungen** sind eine sehr gute Idee

Im besten Fall hat die Abkürzung **mehrere Bedeutungen**
-->

---
layout: two-cols
info: Naming 2.2
---

<h1>Naming</h1>

<div v-click-hide class="" style="padding-right: 2vw;">
  <h2>Use abbreviations and A.C.R.O.N.Y.M.S.</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  col, fn, gt, arg, obj,
  opts, conf, imo, bg, chk, ge
  ```
</div>

<div v-after class="" style="padding-right: 2vw;">
  <h2>Use foreign, made up or lesser known, alternative words with the same meaning</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reprezenti, opcioj, lischtä,
  grid, expense, humptyDumpty
  ```
</div>

::right::


```js {10,16,20|4,5,9,12-15}
/**
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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

<!--
Ebenfalls sehr wirkungsvoll

- **Fremdsprachen** verwenden
- Lokale **Dialekte**
- **Mehrdeutige** Wörter
- **Erfundene oder fiktionale** Wörter
-->

---
layout: two-cols
info: Naming 3.1
---

<h1>Naming</h1>

<div v-click-hide class="" style="padding-right: 2vw;">
  <h2>Use foreign, made up or lesser known, alternative words with the same meaning</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reprezenti, opcioj, lischtä,
  grid, expense, humptyDumpty
  ```
</div>

<div v-after class="" style="padding-right: 2vw;">
  <h2>Misspell everything</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reandom, randem, 
  eveerything, everyting, evrything, 
  vaule, vlaue, vale
  ```
</div>

::right::

```js {4,5,9,12-15|13,15,16}
/**
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The array to be filtered.
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

<!--
**Rechtschreibfehler** einbauen

Dadurch lassen sich auch **Variationen von Variablennamen** generieren

**Verwechslungsgefahr** für Elemente steigt bei Amateuren

Erzeugt **Unsicherheit**
-->

---
layout: two-cols
info: Naming 4.1
---

<h1>Naming</h1>

<div v-click-hide class="" style="padding-right: 2vw;">
  <h2>Misspell everything</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```text
  reandom, randem, 
  eveerything, everyting, evrything, 
  vaule, vlaue, vale
  ```
</div>

<div v-after class="" style="padding-right: 2vw;">
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
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The array to be filtered.
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

<!--
Verwende **zufällige Gross-/Kleinbuchstabenkombinationen**

**Lesbarkeit** für unerfahrene Entwickler **nimmt exponentiel ab**
-->

---
layout: two-cols
info: Naming 4.1
---

<h1>Naming</h1>

<div class="" style="padding-right: 2vw;">
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
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The array to be filtered.
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
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The array to be filtered.
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

<!--
So, dass **sieht schon viel besser** aus

Code, bei dem **Anfänger merkliche Schwierigkeiten** haben werden
-->

---
layout: center
class: text-center
info: Comments
---

<h1>Comments</h1>

<div v-click>

```
<!-- TODO: update this -->
```

</div>

<!--
Kommentare

Werden **oft von anderen eingefordert**

**Profis kennen ihren Code** und brauchen keine "Hilfestellung"

Maxime: **Kommentiere alles Selbsterklärende, ignoriere alles Komplexe**
-->

---
layout: center
info: Comments 1.1
---

```js
/**
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The array to be filtered.
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

<!--
Wir **wenden unsere Verbesserung** auf das Resultat aus dem **letzten Kapitel** an
-->

---
layout: two-cols
info: Comments 2.1
---

<h1>Comments</h1>

<div class="" style="padding-right: 2vw;">
  <h2>Write lying or nonsensical comments</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  /**
   * Make snafucated.
   */
  function makeSnafucated() {}
  ```
</div>

::right::

<div v-click-hide class="hide-for-real">

```js {all|2,5}
/**
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} lischtä - The array to be filtered.
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

</div>

<div v-after class="hide-for-real">

```js {2,5}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
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

</div>

<!--
Verwende wenn möglich **irreführende, sinnlose oder lügende** Kommentare
-->

---
layout: two-cols
info: Comments 3.1
---

<h1>Comments</h1>

<div v-click-hide class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Write lying or nonsensical comments</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  /**
   * Make snafucated.
   */
  function makeSnafucated() {}
  ```
</div>

<div v-after class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Document the obvious. Document the "how", not "why".</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  i++; // Add '1' to 'i'.
  ```
</div>

::right::

<div v-click-hide class="hide-for-real">

```js {2,5|12,16,20}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
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

</div>

<div v-after class="hide-for-real">

```js {12-16,20}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const res = [];

  // Loop lischtä items.
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; // Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      res.push(vaule); // Push value.
    }
  }

  return res; // Return result.
}
```

</div>

<!--
Dokumentiere das **Offensichtliche**

Beschreibe das **Wie**, **nicht das Warum**
-->

---
layout: two-cols
info: Comments 4.1
---

<h1>Comments</h1>

<div v-click-hide class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Document the obvious. Document the "how", not "why".</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  i++; // Add '1' to 'i'.
  ```
</div>

<div v-after class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Use comments instead of variables</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  return value * 1000 * 60; // minutes * milliseconds * seconds = X minutes
  ```
</div>

::right::

<div v-click-hide class="hide-for-real">

```js {12-16,20|10,21,25}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const res = [];

  // Loop lischtä items.
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; // Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      res.push(vaule); // Push value.
    }
  }

  return res; // Return result.
}
```

</div>

<div v-after class="hide-for-real">

```js {10,21,25}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; // ResultList.

  // Loop lischtä items.
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; // Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      a.push(vaule); // Push value to ResultList.
    }
  }

  return a; // Return ResultList.
}
```
</div>

<!--
Verwende **Kommentare, anstelle von aussagekräftigen Variablennamen**
-->

---
layout: two-cols
info: Comments 5.1
---

<h1>Comments</h1>

<div v-click-hide class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Use comments instead of variables</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  return value * 1000 * 60; // Minutes * Milliseconds * Seconds = X Minutes
  ```
</div>

<div v-after class="hide-for-real" style="padding-right: 2vw;">
  <h2>Use various formats</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  /* Some men just want to watch the world burn. */
  
  // Some men just want to watch the world burn.
  
  /**
   * Some men just want to watch the world burn.
   */
  
  //
  // Some men just want to watch the world burn.
  //
  
  /** Some men just want to watch the world burn. **/
  ```

</div>

::right::

<div v-click-hide class="hide-for-real">

```js {10,21,25|10,12,14}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; // ResultList.

  // Loop lischtä items.
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; // Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      a.push(vaule); // Push value to ResultList.
    }
  }

  return a; // Return ResultList.
}
```

</div>

<div v-after class="hide-for-real">

```js {10,12-14,17,23}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* ResultList. */

  //
  // Loop lischtä items.
  //
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; ////// Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      /**** Push value to ResultList. ****/
      a.push(vaule);
    }
  }

  return a; // Return ResultList.
}
```

</div>

<!--
Nutze **wahllose Kommentarformate**
-->

---
layout: two-cols
info: Comments 5.1
---

<h1>Comments</h1>

<div v-click-hide class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Use various formats</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  /* Some men just want to watch the world burn. */
  
  // Some men just want to watch the world burn.
  
  /**
   * Some men just want to watch the world burn.
   */
  
  //
  // Some men just want to watch the world burn.
  //
  
  /** Some men just want to watch the world burn. **/
  ```

</div>

<div v-after class="hide-for-real" style="padding-right: 2vw;">
  <h2>Finally, you can also apply anything from the 'Naming' section.</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  // Sm3 M3n jst want
  //      to WaTch THE WORLD BURN.
  ```

</div>

::right::

<div v-click-hide class="hide-for-real">

```js {10,12-14,17,23|2,4,5,10,13,23,28}
/**
 * Get keys of object.
 *
 * @param {array} lischtä - The array to be filtered.
 * @param {function} thanos - Let him crush your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* ResultList. */

  //
  // Loop lischtä items.
  //
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; ////// Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      /**** Push value to ResultList. ****/
      a.push(vaule);
    }
  }

  return a; // Return ResultList.
}
```

</div>

<div v-after class="hide-for-real">

```js {2,4,5,10,13,23,28}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* a */

  //
  // Oolp lischtä items.
  //
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; ////// Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      /**** Posh value to A ****/
      a.push(vaule);
    }
  }

  return a; // Return a.
}
```

</div>

<!--
Abschliessend

- JSDoc lückenhaft verwenden
-->

---
layout: two-cols
info: Naming 4.1
---

<div style="padding-right: 0.5vw;">

```js
/**
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* a */

  //
  // Oolp lischtä items.
  //
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; ////// Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      /**** Posh value to A ****/
      a.push(vaule);
    }
  }

  return a; // Return a.
}
```

---
layout: center
class: text-center
info: Hints
---

<h1>Additional hints</h1>

<img src="https://media.giphy.com/media/mxQUQbIjXMSwo/giphy.gif">

<!--
**Tipps für Fortgeschrittene**
-->

---
layout: two-cols
info: Hints 1.1
---

<h1>Hints</h1>

<div class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Make conditions as complex as possible</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  // 1
  if (!isNotAvailable && isNotVisible) {}

  // 2
  return this.value || this.type === 'button' ? 'button' : null;

  // 3
  function isOrderButtonDisabled() {
    return !this.isLoggedInUser
      || (this.items && !this.items.length)
      || this.getRequestIsRunning
      || this.backToCartRequestIsRunning
      || this.placeOrderRequestIsRunning
      || this.placeQuoteRequestIsRunning;
  };
  ```

</div>

::right::

<div v-click-hide class="hide-for-real">

```js {all|17,22-25}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* a */

  //
  // Oolp lischtä items.
  //
  for (
    let ì = 0; // Loop index.
    ì < lischtä.length; ////// Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    if (thanos(vaule, ì, lischtä)) {
      /**** Posh value to A ****/
      a.push(vaule);
    }
  }

  return a; // Return a.
}
```

</div>

<div v-after class="hide-for-real">

```js {17,22-27}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* a */

  //
  // Oolp lischtä items.
  //
  for (
    let ì = 0; // Loop index.
    ì < (lischtä && lischtä.length || 0); ////// Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) {
      continue;
    } else {
      a.push(vaule);
    }
  }

  return a; // Return a.
}
```

</div>

<!--
Schreibe if/else Anweisungen so kompliziert wie möglich

- **Doppelte Verneinung**
- **Inline If/Else** statt **Or** verwenden
- Komplexe Prüfungen **niemals** aufteilen
-->

---
layout: two-cols
info: Comments 2.1
---

<h1>Hints</h1>

<div v-click-hide class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Make conditions as complex as possible</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  // 1
  if (!isNotAvailable && isNotVisible) {}

  // 2
  return this.value || this.type === 'button' ? 'button' : null;

  // 3
  function isOrderButtonDisabled() {
    return !this.isLoggedInUser
      || (this.items && !this.items.length)
      || this.getRequestIsRunning
      || this.backToCartRequestIsRunning
      || this.placeOrderRequestIsRunning
      || this.placeQuoteRequestIsRunning;
  };
  ```

</div>

<div v-after class="hide-for-real" style="padding-right: 2vw;">
  <h2>Drop linebreaks</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  const mappedProducts = products.filter(product => product.isAvailable === true').sort((product_a, productB) => product_a.name.localCompare(productB.name)).map(({ id, name } => ({ id, name }));

  ```
</div>

::right::

<div v-click-hide class="hide-for-real">

```js {15-19,22-27}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* a */

  //
  // Oolp lischtä items.
  //
  for (
    let ì = 0; // Loop index.
    ì < (lischtä && lischtä.length || 0); ////// Check loop position.
    ì += 1 // Update loop index.
  ) {
    const vaule = lischtä[ì];

    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) {
      continue;
    } else {
      a.push(vaule);
    }
  }

  return a; // Return a.
}
```

</div>

<div v-after class="hide-for-real">

```js {15,19}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* a */

  //
  // Oolp lischtä items.
  //
  for (let ì = 0; /* Loop index. */ ì < (lischtä && lischtä.length || 0); /* Check loop position. */ ì += 1 /* Update loop index. */) {
    const vaule = lischtä[ì];

    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) { continue; } else { a.push(vaule); }
  }

  return a; // Return a.
}
```

</div>

<!--
**Verzichte* so oft wie möglich **auf Zeilenumbrüche**

Mit einem **ultraweiten Monitor** kannst du so mehr Code auf dem Bildschirm darstellen als **minderbemittelte Entwickler**

Das Resultat seht ihr auf diesem **Mini-Fernseher** leider nicht
-->

---
layout: two-cols
info: Comments 3.1
---

<h1>Hints</h1>

<div v-click-hide class=" hide-for-real" style="padding-right: 2vw;">
  <h2>Drop linebreaks</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  const mappedProducts = products.filter(product => product.isAvailable === true').sort((product_a, productB) => product_a.name.localCompare(productB.name)).map(({ id, name } => ({ id, name }));

  ```

</div>

<div v-after class="hide-for-real" style="padding-right: 2vw;">
  <h2>Get rid of semicolons and brackets</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  const a = 'foo'
  const b = 'baa'

  if (!c) return
  ```
</div>

::right::

<div v-click-hide class="hide-for-real">

```js  {15,19|10,16,19,22}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = []; /* a */

  //
  // Oolp lischtä items.
  //
  for (let ì = 0; /* Loop index. */ ì < (lischtä && lischtä.length || 0); /* Check loop position. */ ì += 1 /* Update loop index. */) {
    const vaule = lischtä[ì];

    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) { continue; } else { a.push(vaule); }
  }

  return a; // Return a.
}
```

</div>

<div v-after class="hide-for-real">

```js {10,16,19-21,24}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = [] /* a */

  //
  // Oolp lischtä items.
  //
  for (let ì = 0; /* Loop index. */ ì < (lischtä && lischtä.length || 0); /* Check loop position. */ ì += 1 /* Update loop index. */) {
    const vaule = lischtä[ì]

    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) continue
    
    a.push(vaule)
  }

  return a // Return a.
}
```

</div>

<!--
Spare **Tastenanschläge**

Nur **Profis wissen**, wo diese Zeichen zwingend zu verwenden sind

**Maskiere Ausführungsabfolgen**
-->

---
layout: two-cols
info: Comments 4.1
---

<h1>Hints</h1>

<div class="hide-for-real" style="padding-right: 2vw;">
  <h2>Use random linebreaks, indents and quotation marks</h2>
  <br>&nbsp;
  <br>&nbsp;

  ```js
  const a = "foo"

  const b = 'baa'
  const c = `bar`
  if (!c)   return
  ```
</div>

::right::

<div v-click-hide class="hide-for-real">

```js  {all}
/**
 * Get_keys of Obj.
 *
 * @param {array} lischtä - The to be Filtred Array.
 * @param {Function} thanos - Let him CRUSH your team members.
 *
 * @returns {*[]}
 */
function filTerArRayelEmentS(lischtä, thanos) {
  const a = [] /* a */

  //
  // Oolp lischtä items.
  //
  for (let ì = 0; /* Loop index. */ ì < (lischtä && lischtä.length || 0); /* Check loop position. */ ì += 1 /* Update loop index. */) {
    const vaule = lischtä[ì]

    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) continue

    a.push(vaule)
  }

  return a // Return a.
}
```

</div>

<div v-after class="hide-for-real">

```js
/**
 * Get_keys of
 * Obj.
 * 
 * 
 * @param   {array} lischtä - The to be Filtred Array.
 * @param {Function } thanos - Let him CRUSH your team members.
 * 
 * @returns { *[]}
 */

function filTerArRayelEmentS(lischtä,     thanos) {
  
  const a = [] /* a */
  //
  // Oolp lischtä items.
  //
  
  for (let ì = 0; /* Loop index. */ 
       ì < (lischtä && lischtä.length || 0); /* Check loop position. */ ì += 1 /* Update loop index. */
  ) {
    const  vaule = lischtä[ì]
    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) continue
    a.push(vaule)
  }
  return a // Return a.
}
```

</div>

<!--
Wahllose **Zeilenabstände und Anführungszeichen**

**Profis können komplexen Code lesen**
-->

---
layout: two-cols
info: Naming 4.1
---

<div style="padding-right: 0.5vw;">

```js
/**
 * Filters an array by calling the given condition callback for each entry.
 *
 * @param {array} sourceArray - The array to be filtered.
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
 * Get_keys of
 * Obj.
 *
 *
 * @param   {array} lischtä - The to be Filtred Array.
 * @param {Function } thanos - Let him CRUSH your team members.
 *
 * @returns { *[]}
 */

function filTerArRayelEmentS(lischtä,     thanos) {

  const a = [] /* a */
  //
  // Oolp lischtä items.
  //

  for (let ì = 0; /* Loop index. */
       ì < (lischtä && lischtä.length || 0); /* Check loop position. */ ì += 1 /* Update loop index. */
  ) {
    const  vaule = lischtä[ì]
    /**** Posh value to A ****/
    if (!thanos(vaule, ì, lischtä) === true) continue
    a.push(vaule)
  }
  return a // Return a.
}
```

<!--
Ein **Meisterwerk**

**Flüche und emotionale Ausbrüche von Amateur-Kollegen** unterstreichen die professionelle Qualität des Codes
-->

---
layout: center
class: 'text-center'
info: Hints
---

<h1>WTFAA****RG!</h1>

<img src="https://media.giphy.com/media/LTM9zeisAfX9xQbz8Y/giphy.gif">

---
layout: center
class: text-center
info: Hints
---

<h1>Thank you!</h1>

<!--
**Herzlichen Dank** für eure Aufmerksamkeit

Wer sich **gut unterhalten** gefühlt hat, **darf sich gerne bei uns bewerben**

Wer sich **inspiriert gefühlt** hat, **lieber nicht** 😉
-->
