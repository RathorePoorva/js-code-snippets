# javascript-code-snippets

```
const a = {
  i: 1,
  toString: function () {
    return a.i++;
  }
}
if(a == 1 && a == 2 && a == 3) {
  console.log('Hello World!');
}
```
OUTPUT: 
Hello World!

```
// Compare an NaN to another
if (NaN === NaN) {
  console.log("NaN === NaN");
} else if (NaN == NaN) {
  console.log("NaN == NaN");
} else {
  console.log("NaN cannot be compared to NaN");
}
```
OUTPUT:

```
// Compare lowerCase with uppercase alphabets
if("a" > "Z"){
  console.log("a > Z");
}
```
OUTPUT:

```
function fun(n){
  if(n<1){
    return;
  }else{
    console.log(n);
    fun(n-1);
    console.log(n);
  }
}
fun(3);
```
OUTPUT:
3  2  1  1  2  3

```
console.log(1);
setTimeout(function() {
  console.log(2);
}, 1000);
setTimeout(function() {
  console.log(3);
}, 0);
console.log(4);
```
OUTPUT:
1  4  3  2
