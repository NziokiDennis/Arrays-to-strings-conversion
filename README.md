# Arrays-to-strings-conversion
var arr = ['a', 'á', 'b', 'c']
function upper_lower (a, b, i) {
 //...do something here
 b = i & 1 ? b.toUpperCase() : b.toLowerCase();
 return a + ',' + b
}
arr = arr.reduce(upper_lower); // "a,Á,b,C"
