#### Problem 2
```
let i = 0;
function sumRecursion2(a){
  if (i === a.length - 1) return a[i];
  return a[i++] + sumRecursion2(a);
}
```

#### Problem 4(a)

```
function isPalindrome(a){
  if (a.length <=1 ) return true
  return a[0] === a[a.length -1] && isPalindrome(a.slice(1,a.length-1))
}
```

#### Problem 4(c)

```
function changeBase(value, base){
  // base case
  if (value == 0) return "";
  // recursing case
  let reminder = value%base;
  value = Math.floor(value/base);

  return changeBase(value,base) + reminder;
}
```
