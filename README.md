# Snipper

## A collection of common javascript statement snippets for faster development in [Visual Studio Code](https://code.visualstudio.com/).

### Feel free to install the extension from VS Code or from [here](https://marketplace.visualstudio.com/items?itemName=RimonAhmed.snip-js).

### See the [demo](#demo).

***

* [Assignments](#assignments)
* [Functions](#functions)
* [Conditions](#conditions)
* [Validations](#validations)
* [DOM manipulations](#dom-manipulations)
* [Console](#console)
* [Destructuring](#destructuring)
* [Others](#others)

***

## Assignments

#### `la =>` let assignment

#### `va =>` var assignment

#### `ca =>` const assignment

#### `aa =>` array assignment


#### `oa =>` object assignment

***

## Functions

#### `af =>` arrow function

#### `nf =>` named function

***

## Conditions

#### `ec =>` equal condition

#### `nec =>` not equal condition

#### `gtc =>` greater than condition

#### `ltc =>` less than condition

#### `getc =>` greater equal than condition

#### `letc =>` less equal than condition

#### `oc =>` or condition

#### `ac =>` and condition

#### `co =>` condition operator

***

## Validations

#### `zlv =>` zero length validation

#### `plv =>` positive length validation

#### `esv =>` empty string validation

#### `nesv =>` not empty string validation

#### `nv =>` null validation

#### `nnv =>` not null validation

#### `uv =>` undefined validation

#### `nuv =>` not undefined validation

#### `iov =>` instance of validation

#### `av =>` array validation

#### `ov =>` object validation

#### `cv =>` contains validation

#### `dcv =>` doesn't contain validation

***

## DOM manipulations

#### `ael =>` add event listener

#### `rel =>` remove event listener

#### `cel =>` create element

#### `ach =>` append child

#### `rch =>` remove child

#### `gei =>` get element by id

#### `gec =>` get element by class name

#### `get =>` get element by tag name

#### `qs =>` query selector

#### `qsa =>` query selector all

***

## Console

#### `cl =>` console log

#### `cw =>` console warn

#### `ce =>` console error

***

## Destructuring

#### `od =>` object destructuring

#### `ad =>` array destructuring

***

## Demo

#### These are the results after executing each and every snippet from the collection.

```js
// Assignments

let name = value // la
var name = value // va
const name = value // ca
let name = { // oa
   "key": value
}
let name = [value1, value2] // aa

// Functions

const name = (param) => { // af
    
}
function name (param) { // nf
    
}

// Conditions 

value1 === value2 // ec
value1 !== value2 // nec
value1 > value2 // gtc
value1 < value2 // ltc
value1 >= value2 // getc
value1 <= value2 // letc
condition1 || condition2 // oc
condition1 && condition2 // ac
let name = condition ? value1 : value2 // co

// Validations

value.length === 0 // zlv
value.length > 0 // plv
value === "" // esv
value !== "" // nesv
value === null // nv
value !== null // nnv
typeof value === "undefined" // uv
typeof value !== "undefined" // nuv
value1 instanceof value2 // iov
Array.isArray(value) || value.length // av
Object.keys(value).length === 0 && value.constructor === Object // ov
value1.indexOf(value2) > -1 // cv
value1.indexOf(value2) === -1 // dcv

// DOM manipulations

document.addEventListener("event", (param) => { // ael
    
})
document.removeEventListener("event", (param) => { // rel
    
})
document.createElement("value") // cel
document.appendChild("value") // ach
document.removeChild("value") // rch
document.getElementById("value") // gei
document.getElementsByClassName("value") // gec
document.getElementsByTagName("value") // get
document.querySelector("value") // qs
document.querySelectorAll("value") // qsa

// Console 

console.log(value) // cl
console.warn(value) // cw
console.error(value) // ce

// Destructuring

let { value1 } = value2 // od
let [value1, value2] = value3 // ad
```

***

##### For questions, do not hesitate to write me an email - *rimonians@gmail.com*

##### Leave a star if you like and find the snippets helpful!

*** 

**Code by Rimon Ahmed. Copyright 2022**