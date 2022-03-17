# Code Snippests


## Date
```js
// javascript date today dd mm yyyy
var today = new Date();
var dd = String(today.getDate()).padStart(2, '0');
var mm = String(today.getMonth() + 1).padStart(2, '0'); //January is 0!
var yyyy = today.getFullYear();

today = mm + '/' + dd + '/' + yyyy;
document.write(today);

// js date format yyyy-mm-dd
yourDate.toISOString().split('T')[0]

//convert date format from yyyy-mm-dd to dd-mm-yyyy using value javascript
date.value.split("-").reverse().join("-");      //"2021-01-17" --> 17-01-2021

```