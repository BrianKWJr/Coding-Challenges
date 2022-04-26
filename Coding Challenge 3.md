function FirstReverse(str) { 

 var splitString = str.split("");

  var reverseArray = splitString.reverse();

  var joinArray = reverseArray.join("")
   
  return str.split("").reverse().join("");; 

}
   
// keep this function call here 
console.log(FirstReverse(readline()));