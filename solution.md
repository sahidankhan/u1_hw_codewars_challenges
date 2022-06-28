## Return Negative

```js
const makeNegative = (num) => {
    if(num <= 0){
        conaole.log(num)
    }else{
        console.log(num * -1)
    }
}

makeNegative(1)
makeNegative(-5)
makeNegative(0)
```

## Sum of Positive

```js
// Example [1,-4,7,12] => 1 + 7 + 12 = 20
const sumArr = (num) =>{

if(num < 0){
    console.log('undefined')
}else{
    for let(i = 0; i < num.length;i++)
    if(num[i] >= 0){
        sum = sum + num[i]
    }console.log(sum)
}}
sumArr([1,-4,7,12])

```

## Function 2

```js
let squareNum = Math.pow(2)
console.log("4*4 = ", squareNum)
```

## Sum Arrays

```js
const sum =(num) =>{
    for (let i=0; i < num.length; i++)
    if(num[i] <= 0){
        console.log(0)
    }else if(
     sum = sum + num[i]){
        console.log(sum)
     }
}
```

## Reversed Strings

```js

reverseString = (str) =>{

  let newString = ("world");
    for (let i >= 0;i = str.length - 1; i--) 
        newString += str[i];
}
    console.log(newString);
```
