#### 数组是否按顺序排列
```
function compare(a, b) {
    return a - b;
    // 根据返回值判断
    // <0 正续 [a,b]
    // >0 逆序 [b,a]
}
sort(Array, compare)；
```
复制数组

```
var arr1 = [1,2,3];
var arr2 = arr1.concat();
console.log(arr1,arr2);
```
```
//ES6 展开操作符
var arr1 = [1,2,3,4];
var arr2 = [...arr1];
console.log(arr1,arr2)
```