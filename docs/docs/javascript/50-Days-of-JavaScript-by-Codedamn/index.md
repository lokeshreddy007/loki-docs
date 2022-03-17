# 50 Days of JavaScript! by Codedamn

### Function which returns a random number in the given range
Create a function which returns a random number in the given range of values both inclusive

Challenges (0/2 done)

- [ ] randomNumberGeneratorInRange(10, 50) should return a number between 10-50 (inclusive)
- [ ] randomNumberGeneratorInRange(100, 200) should return a number between 100-200 (inclusive)

```js
function randomNumberGeneratorInRange(min, max) {
    // write your solution here

    return Math.floor(Math.random() * (max - min + 1)) + min
}

console.log(`My random number: ${randomNumberGeneratorInRange(5, 100)}`)

```

### Write a program to reverse a string
+ String can be reversed by iterating it and storing it in reverse order
+ String can also be reversed by converting it to array, then joining it after reversing

Challenges (0/3 done)

- [ ] reverseAString("JavaScript is awesome") should return "emosewa si tpircSavaJ"
- [ ] reverseAString("Peter Parker is Spiderman") should return "namredipS si rekraP reteP"
- [ ] reverseAString("codedamn") should return "nmadedoc"

```js
const str = "JavaScript is awesome"

function reverseAString(str) {
    // write your solution here
    var newString = "";
    for (var i = str.length - 1; i >= 0; i--) {
        newString += str[i];
    }

    return newString
}

console.log(`Reversed string is: ${reverseAString(str)}`)

```

### Write a program to reverse a given integer number
+ The remainder of the number can be fetched and the number can be divided by 10 to remove the the digit in loop till number becomes 0
+ A simple approach to reverse a number could also be to convert it in to a string and then reverse it

 Challenges (0/3 done)
 
- [ ] reverseGivenInteger(3849) returns 9483
- [ ] reverseGivenInteger(2222) returns 2222
- [ ] reverseGivenInteger(1002) returns 2001

```js
const num = 3849;

function reverseGivenInteger(num) {
    // write your solution here
    let st = num.toString();
    let rev_num = st.split('').reverse().join('');
    return Number(rev_num);
}

console.log(`Reversed integer is: ${reverseGivenInteger(num)}`)
```
