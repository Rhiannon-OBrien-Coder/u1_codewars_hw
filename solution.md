## Return Negative

```js
function MakeNegative(num1) {
    if (num1 <= 0){
    return(num1)
    } else {
        return(num1 * -1)
    }
}

console.log(MakeNegative(-1))
console.log(MakeNegative(5))
console.log(MakeNegative(0))
```

## Sum of Positive

```js
const myArray = [1, -4, 7, 12]

function sum(anArray){
    let num1 = 0
    for (let i = 0; i < anArray.length; i++){
        if (anArray[i] > 0) {
            num1 = anArray[i] + num1
        }
    }
    return(num1)
}

console.log(sum(myArray))
```

## Function 2

```js
function square(num1) {
    return(num1 * num1)
}

console.log(square(-1))
console.log(square(5))
console.log(square(0))
```

## Sum Arrays

```js
const myArray = [1, 5.2, 4, 0, -1]
const mySecondArray = [-2.398]
const myThirdArray = []

function sum(anArray){
    let num1 = 0
    for (let i = 0; i < anArray.length; i++){
            num1 = anArray[i] + num1  
    }
    return(num1)
}

console.log(sum(myArray))
console.log(sum(mySecondArray))
console.log(sum(myThirdArray))
```

## Reversed Strings

```js
let world = 'world'

function reversie(aString){
    let backsies = ""
    for (let i = aString.length-1; i >= 0 ; i--) {
        backsies = backsies + aString[i]
    }
    return(backsies)
}

console.log(reversie(world))
```
