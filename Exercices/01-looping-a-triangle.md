# Looping a triangle

Write a loop that makes seven calls to console.log to output the following triangle:

```js
#
##
###
####
#####
######
#######
```

It may be useful to know that you can find the length of a string by writing .length after it.

```js
let abc = "abc";
console.log(abc.length);
// → 3
```
## Solution

```js
let result = '#';
for (let i = 0; i < 7; i++) {
    console.log(result);
    result += '#';
}
```