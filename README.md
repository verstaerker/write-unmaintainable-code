# How to write unmaintainable code

<img src="assets/title.png" style="max-width: 600px;">

<details>
  <summary>Source</summary>

  ```js
  // Who wrote this bullschit?
  
  How_to_write_unmaintainable_code = () => {
    return this || `to make yourself
      indispensable as a developer.`
  }
  ```
</details>

## Tools to create unmaintainable code

### Naming

#### Use single letters, symbols or accented letters

> `a`, `b`, `c`, `🍬`, `𝘼`, `𝟙`. `í`, `ä`

Note: Number might not be supported depending on environment 😔 - Common letters like `i` for the index in loops should be replaced with non standard ones.

#### Use abbreviation or A.C.R.O.N.Y.M.S.

> `col`, `el`, `gt`, `arg`, obj`, `opts`, `conf`, `md`, `imo`, `bg`, `chk`, `ge`

At best, these have two or more meanings depending on context.

#### Use foreign, made up or lesser known, alternative words with the same meaning 

> `reprezenti`, `opcioj`, `grid`, `expense`, `humptyDumpty`

Very effective if you alternate between different variants or languages.

#### Misspell everything

> `reandom`, `eveerything`, `everyting`, `evrything`, `vaule`, `vlaue`, `vale`

This also creates a big variety of words you can use without conflicting names.

#### Use words that are hard to read and write or/and also look different when used in plural

> `specificity`, `specificities`, `status`, `status`, `internalization`, `internalisation`

#### Use random capitalization or format

> `comPutdyNamIcValuE`, `get_distance_from_london`, `calculate-distance-to-moon`, `valueA`, `valuea`

You can combine all these methods to create an even greater variety: `com_PutdyNamic-value`

#### Use local variables to shadow global/reserved words

> `window`, `Function`, `Default`, `float`, `boolean`

#### Example

<details>
<summary>Show</summary>

### Bad

```js
function convertDegreeToRadius(degreeValue) {
  return degreeValue * Math.PI / 180;
}

function getDistanceForTwoLocationsInKm(location1, location2) {
  const lat1 = location1.lat;
  const lon1 = location1.lon;
  const lat2 = location2.lat;
  const lon2 = location2.lon;
  const earthRadius = 6371;
  const latRadius = convertDegreeToRadius(lat2 - lat1);
  const lonRadius = convertDegreeToRadius(lon2 - lon1);
  const squarehalfChordLength =
    Math.sin(latRadius / 2) * Math.sin(latRadius / 2) +
    Math.cos(convertDegreeToRadius(lat1)) * Math.cos(convertDegreeToRadius(lat2)) *
    Math.sin(lonRadius / 2) * Math.sin(lonRadius / 2);

  const angularDistance = 2 * Math.atan2(Math.sqrt(squarehalfChordLength), Math.sqrt(1 - squarehalfChordLength));
  
  return earthRadius * angularDistance;
}
```

### Good

```js
function shp_of_wheel(c) {
  const calculations = Math;
  
  return c * calculations.PI / (0.5 * 360);
}

function retDisFAB(sta, sto) {
  const la_ny = sta.lat;
  const lo_ny = sta.lon;
  const la_london = sto.lat;
  const lo_londen = sto.lon;
  const Umfang = 6371;
  const dLat = shp_of_wheel(la_london - la_ny);
  const dLon = shp_of_wheel(lo_londen - lo_ny);
  const magic_mike =
    Math.sin(dLat * 0.5) * Math.sin(dLat * 0.5) +
    Math.cos(shp_of_wheel(la_ny)) * Math.cos(shp_of_wheel(la_london)) *
    Math.sin(dLon * 0.5) * Math.sin(dLon * 0.5);

  const corner_Distance = 2 * Math.atan2(Math.sqrt(magic_mike), Math.sqrt(1 - magic_mike));

  return Umfang * corner_Distance;
}
```
</details>
