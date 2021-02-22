
# Javascript Crash Course 

{{quote {author: "Prophet Muhammad"}

"When a man dies, his deeds come to an end except for three things: Sadaqah Jariyah (ceaseless charity); a knowledge which is beneficial, or a virtuous descendant who prays for him (for the deceased)."

quote}}

- [Javascript Crash Course](#javascript-crash-course)
  - [Ekrana yazdırmak](#ekrana-yazdırmak)
  - [Değişkenler](#değişkenler)
    - [Değişkenler Tipleri](#değişkenler-tipleri)
  - [Matematik sembolleri](#matematik-sembolleri)
  - [Atama işaretleri](#atama-işaretleri)
  - [Artış Azalış işartleri](#artış-azalış-işartleri)
  - [Data Tipleri](#data-tipleri)
    - [Metinler](#metinler)
  - [Şartlar](#şartlar)
    - [Karşılaştırma işaretleri](#karşılaştırma-işaretleri)
    - [Karşılaştırma kısaltması](#karşılaştırma-kısaltması)
    - [Mantıksal](#mantıksal)
    - [İkili sayılar](#i̇kili-sayılar)
    - [Switch](#switch)
  - [Döngüler](#döngüler)
  - [Veri yapıları](#veri-yapıları)
  - [Diziler](#diziler)
    - [Her element için](#her-element-için)
    - [For Of](#for-of)
    - [For in](#for-in)
  - [Maps](#maps)
  - [Sets](#sets)
  - [Diğer atama işaretleri](#diğer-atama-işaretleri)
  - [Fonksiyonlar](#fonksiyonlar)
  - [Hazır Kütüphaneler](#hazır-kütüphaneler)
    - [Matematik](#matematik)
    - [Tarih](#tarih)
    - [Hazır fonskyonlar](#hazır-fonskyonlar)
    - [Son Kullanım Tarihi örneği](#son-kullanım-tarihi-örneği)
  - [Alıştırma](#alıştırma)
    - [Asal sayılar](#asal-sayılar)
  - [Sınıflar](#sınıflar)
  - [Hata yakalama (debugging)](#hata-yakalama-debugging)
  - [Modules](#modules)
  - [Generators](#generators)
  - [Promises](#promises)
  - [Extras](#extras)

## Ekrana yazdırmak

```
console.log(34);
```

## Değişkenler

```
x + y = 5 
x = 1 
y = ? 
```

```
x + y + z = 25
x = 10 
z =  y + y  
```

### Değişkenler Tipleri

```
let 
var
const
```

```
const x = 10; 
const y = 14;
x = 11;
console.log(x) 
```

```
let x = 2, y = 1;
console.log(x+y);
let z= 5;
let h= 20;
console.log(h/z)
```

```
var x = 10 
var y = 20 
console.log(x*y)
```
## Matematik sembolleri


```
+
-
/
*
%
**
```

```
console.log(1+2)
console.log(4*5)
```


## Atama işaretleri

```
=
*=
/=
%=
+=
-=
```


```
let x =1
x += 1
console.log(x) 
x *= 4
```

Logical 

```
<<=
>>=
&= And
^= Exor 
|= Or
```
```
let x = 1 
console.log(x)
x &= 0
console.log(x)
```
## Artış Azalış işartleri

```
A++
A--
++A
--A
```

```
let x = 0
console.log(x)
console.log(x++)
console.log(++x)
```


## Data Tipleri

```
undefined 
Boolean // True, False  
String   
Object
Function
Null    
```

```
let h = undefined
let t = true 
let x = "Hello"
let n = Null
let b = function (x) {return x*2}
let ob = {h:1,b:2}
```

Changing between types
The advantages of each type

```
Number // -(2^53 − 1) and 2^53 − 1).
+Infinity, -Infinity, and NaN
```

```
let x = 2 
let b = 0/0
let mi= -100/0
let pl= 100/0
```

```
BigInt
```

```
console.log(Number.MAX_VALUE)
// console.log(BigInt(Number.MAX_VALUE))
```

```
let x = 42;
console.log(typeof x)    
x   = 'bar'; 
x   = true;  
```

```
let x= "Hello";
console.log(result)
let y= "world"
console.log(x+y)
let z= 1;
console.log(x+y+z)
```

[Data Tipler](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)

### Metinler

```
const string1 = "A string";
const string2 = 'Also a string';
const string3 = `another string`;
```

```
const string1 = `${1+2} = 3 , 1+1 = 2`;
```

## Şartlar

```
if
ifelse 
switch
```

### Karşılaştırma işaretleri

```
< 
<= 
>
>=
==
!=
```

```
console.log(1 < 3 )
```


```
let x= 2, y= 4;
if(x < y ){

}

if (x > y ){

}
```

```
if(){}
else{}
```

```
if(){}
else if(){}
else()
``` 

### Karşılaştırma kısaltması

```
(condition)?ifTrue:ifFalse;
```

```
a = (4 > 5 )? true: false; 
console.log(a)
```

### Mantıksal 

```
&&
||
```

```
let x= (false&&true&&false)
console.log(x)
```

```
true,true
false,false
true,false
```

### İkili sayılar

```
&
|
^
```

İkili sayılar 

### Switch

```
let name = "Ahmad"
switch(){
    case "Ahmad":
          console.log("Ahmad is a loyal person")
        break;
    case "Sam":
          console.log("Sam is not home.")
        break; 
    case "Jhon":
          console.log("Jhon is still outside.")
        break;
    default:
      console.log("The name is not defined")

}
```
```
```

## Döngüler

```
for(){}
while(){}
do{}while()
```

```
break
continue
Label
```

```
for(let i=0; i< 10; i++){
    console.log(i)
}
```

```
let result =0;
for(let i=1; i< 20; i=i+1){
    if(x%2 == 0 ){
      console.log(i)
    }
}
console.log(result)
```

```
let x=0
let result1=0;
while(x < 150 ){
    if(x%5 == 0){
      x++
    }
}
console.log(x)
```

```
let result = 0;
for(let i = 0 ; i < 100 ; i ++ ){
  result += i;
}
console.log(result)
```

```
let n = 100
console.log((n*(n+1))/2)
```


## Veri yapıları

```
Array:Index
Map:Key-Value 
Set:Only one.
```

## Diziler

```
let ulama = ["ibn haytham" , "omar khayyam" , "al-battani" , "Al-harezmi" , "ibn-sina" , "ibn-nafis"]
console.log(ulama[1])
console.log(ulama.length)
```


### Her element için

```
ForEach
```

```
let ulama = ["ibn haytham" , "omar khayyam" , "al-battani" , "Al-harezmi" , "ibn-sina" , "ibn-nafis"]
ulama.forEach(element => console.log(element));
```

### For Of

```
for..of
```

```
const Books = ['Book of Optics', 'Rubaiyat', `Kitab Al-Zij al-Sabi’`, "Algebra", `The Canon of Medicine` , `Al-Shamil fi al-Tibb`];
for (const element of Books) {
  console.log(element);
}
```
### For in

```
for..in
```

```
const scholarAndArea = { `ibn haytham`: `Optics`, `al-kharezmi`: `Algebra`, `ibn-sina`: `Medics` };

for (const property in scholarAndArea) {
  console.log(`${property}: ${scholarAndAreat[property]}`);
}
```

## Maps

```
let cities = new Map()
```

```
let cities = new Map()
cities.set('Sudan', "Khartom")
cities.has('Sudan') // true
cities.get('Jordan') // undefined
cities.set('Jordan', "Oman")
cities.get('Jordan') // "Oman"
cities.delete('Syria') // false
cities.delete('Sudan') // true
console.log(cities.size) // 1
```


## Sets

```
let myBooks = new Set()
```

```
let myBooks = new Set()
mySet.add("Sherlock")
mySet.add("Tantawi")
mySet.add("ibn Battuta")
mySet.add("Ali Omari")
mySet.add("Sherlock")
mySet.has("Sherlock")
mySet.delete("Sherlock")
mySet.size
```

## Diğer atama işaretleri

```
[a, b] = [1, 2]
{a, b} = {a:1, b:2}
```

## Fonksiyonlar

```
function multiple2(x){
    return x*2
}

function halfOf(x){
    return x/2
}

const scholarAndArea = { `ibn haytham`: `Optics`, `al-kharezmi`: `Algebra`, `ibn-sina`: `Medics` };

function find(field,map){
for (const property in scholarAndArea) {
  if(scholarAndAreat[property] == field)
    return property
}
}
```

```
function multiplier(x){
    return function (y){
        return y * x
    }
}
```

## Hazır Kütüphaneler


```
Math
Date
```


### Matematik

```
function degToRad(degrees) {
  return Number.parseInt(degrees * (Math.PI / 180));
};

function radToDeg(rad) {
  return Number.parseInt(rad / (Math.PI / 180));
};

console.log(
Math.cos(degToRad(Math.PI)),
Math.sin(degToRad(Math.PI)),
Math.PI
)
```

```
var a, x, y;
var r = 10;

with (Math) {
  a = PI * r * r;
  x = r * cos(PI);
  y = r * sin(PI / 2);
}

console.log(a,x,y)
```

### Tarih

```
let h = new Date
console.log(h)
```

### Hazır fonskyonlar

```
getDate()
getDay()
getFullYear()
getHours()
getMilliseconds()
getMinutes()
getMonth()
getSeconds()
```


### Son Kullanım Tarihi örneği

Algoritma nedir? 

Son Kullanım tarihi Algoritması

```{lang: "java"}
Markete git
Ürün al 
SKT kontrol et
Bitmişse say
Tü ürünler içinn tekrarla.
```

```
let avai=[
2010,
2015,
2000,
2021,
2100,
1914,
2023,
1453
]
let year = new Date().getFullYear()
let count = 0;
for (let i = 0; i < avai.length ; i= i+1){
if(avai[i] <  year){
count ++ }
}
console.log(count)

```

## Alıştırma

### Asal sayılar

{{index "triangle (exercise)"}}

Asal sayıları kontrol eden algoritma yazınız.

{{index [string, length]}}


{{if interactive

```
// Programınız burada yazabilirsiniz.
```
if}}

{{hint

{{index "triangle (exercise)"}}

Asal sayıların kuralından başlayabiliriz. 
sadece kendisine ve bire bölünebilen sayılar ise asal sayılardır. 

Döngüler kullanarak 2 den başlayıp sayıya kadar her hangi bir sayıya bölünmez ise asal sayıdır. Bölünmebilirliği kontrol edebilmesi için (%) işrete kullanabilirsiniz.

hint}}


## Sınıflar

```
Class
```

```
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
    // Getter
  get area() {
    return this.calcArea();
  }
  // Method
  calcArea() {
    return this.height * this.width;
  }
}
let x = new Rectangle(10,20)
console.log(x.area())
```

```
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
    // Getter
  get area() {
    return this.calcArea();
  }
  // Method
  calcArea() {
    return this.height * this.width;
  }
}

Class Square extends Rectangle{
    constructor(size){
        super(size,size)
    }
}
```

## Hata yakalama (debugging)

1- Mantıksal Hatalar

2- Yazım Hataları

3- Çalışma Hataları


```
debugger
try...catch
throw
Error
```

```
nonExistentFunction();
```

```
try {
  nonExistentFunction();
} catch (error) {
  console.error(error);
}
```

```
try {
  throw "Sayı yok."
} catch (error) {
  console.error(error);
}
```

```
let x = new Error("Hatalarından öğren")
```


```
class CustomError extends Error {
  constructor(place, ...params) {
    super(...params)
    if (Error.captureStackTrace) {
      Error.captureStackTrace(this, CustomError)
    }
    this.name = 'CustomError'
    this.place = place
    this.date = new Date()
  }
}

try {
  throw new CustomError('Hata yeri', 'Tekrar dene!')
} catch(e) {
  console.error(e.name)    //CustomError
  console.error(e.place)     
  console.error(e.message) 
  console.error(e.stack)   
}
```

## Modules

type="module"

```
export
import
```

```
export const name = 'square';

export function draw( length, x, y, color) {
  return {
    length: length,
    x: x,
    y: y,
    color: color
  };
}
```

```
export { name, draw, reportArea, reportPerimeter };
```

```
import { name, draw, reportArea, reportPerimeter } from './modules/square.js';
```

## Generators

```
Generator
GeneratorFunction
AsyncGeneratorFunction
AsyncGenerator
```

```
function* generator() {
  yield 1;
  yield 2;
  yield 3;
}
const gen = generator(); 
console.log(gen.next().value); 
console.log(generator().next().value); 
console.log(generator().next().value); 
```

```
function* infinite() {
    let index = 0;

    while (true) {
        yield index++;
    }
}

const generator = infinite(); 
console.log(generator.next().value); 
console.log(generator.next().value); 
console.log(generator.next().value); 
```

## Promises

```
Promise
AsyncFunction
```

```
const CallServer = new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve('You have done.');
  }, 300);
});

CallServer.then((value) => {
  console.log(value);
});

console.log(CallServer);
```

```
const CallServer = new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve('You have done.');
  }, 300);
});

async function asyncCall() {
  console.log('calling');
  const result = await CallServer();
  console.log(result);
}

asyncCall()
```


## Extras

[Kaynak](https://developer.mozilla.org/en-US/)

[Data Tipler](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)

[JS Kaynağı](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)