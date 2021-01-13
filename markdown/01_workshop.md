# JS İLe programlamaya giriş!

{{quote {author: "Hz. Muhammed (S.a.v)"}

Allahtan faydalı ilim isteyin ve fayda vermeyen ilimden Allaha sığının.

quote}}

## Ekrana yazdırmak

```
console.log(34);
```

## Değİşkenler


```
let x = 2, y = 1;
console.log(x+y);
let z= 5;
let h= 20;
console.log(h/z)
```

## Akış kontrolları

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

## Fonksİyonlar

```
function sum(x,y,z){
    return x+y+z 
}

function average(x,y,z){
    return (x+y+z)/3
}


function smaller(x,y){
    if(x<y){
        return x;
    }else {
        return y
    }
}
```
## Matematİk Önreğİ

[Genel Kural](../extras/index.html)

İkinci dereceden denklem

x^2 + 4x + 4 = 0  

```
function delta(a,b,c){
    return Math.sqrt((b*b)-(4*a*c))
}
```
x^2 + 4x + 4 = 0 

Sonuç eksi ise nasıl olur?

```
function quadraticZero(a,b,c){
    return -b/2*a
}

function quadraticMinus(a,b,c){
    return -b/2*a
}

function quadraticPlus(a,b,c){
    return -b/2*a
}
```
## Data Tİplerİ

```
let x= "Hello";
console.log(result)
let y= "world"
console.log(x+y)
let z= 1;
console.log(x+y+z)
```

## Döngüler

```
let result =0;
for(let i=5; i< 20; i=i+1){
    result = i + result;
}
console.log(result)

let x=5
let result1=0;
while(x < 20 ){
    console.log(x)
    x=x+5;
}

for(let i=0; i< 10; i++){
    console.log(i)
}
```

## Dİzİler

```
let x =["a","b","c","d","e","f"]
console.log(x[1])
```
```
let x =["a","b","c","d","e","f"]
console.log(x.length)
```

### Algorİtma örneğİ

Çikolata algoritması

```{lang: "java"}
Markete git 
çikolata ara.
çikolata satın al. 
```

```
let req="Çikolata"
let avai=[
"Şehriye",
"Et",
"Tavuk",
"pilav",
"Çikolata",
"Hıyar",
"Patates",
"Döner"
]

for (let i = 0; i < avai.length ; i= i+1){
if(avai[i]==req){
console.log("vardır")
}
}

```

## Hazır kütüphaneler
Math 

```
console.log(
Math.cos(Math.PI),
Math.sin(Math.PI),
Math.PI
)
```

## Alıştırma

### Üçcgen Çİzİmİ

{{index "triangle (exercise)"}}

Aşağıdaki üçgen çizen yedi kere `console.log` çağıran bir program yazınız.

```{lang: null}
#
##
###
####
#####
######
#######
```

{{index [string, length]}}


{{if interactive



```
// Programın burada yazılır.

```
if}}

{{hint

{{index "triangle (exercise)"}}

ilk etapta [Döngüler kısmı](#Döngüler) referans alırak birden yediye kadar yazdıran bir program yazabilirsiniz. O programı yazdıktan sonra ufak tefek değişikler yapılır. 

Şimdi ise yazılan satırlar ile sayılar arasındaki ilişki üşünün.
hem programınız kare yazdırtırabilirsiniz, her kere bastıktan sonra değişkeni değiştirip yeni bir kare ekleyebikirsiniz bu şekilde (`+= "#"`). 

[Data Tiplerindeki](#Data_Tipleri) bulunan örneklerde kullanabilirsiniz. 

bunları yapınca olmadı mı? belki döngüden önce sabit bir değişken tanımlayıp onun üzerine değişikler yapabilirsiniz? olmaz mı!

hint}}

## Faydalı lİnkler
[Güzel bir okuma kaynağı](https://developer.mozilla.org/en-US/)

[Türkçe İnglizce Sözlük tablosu](../extras/index.html)


