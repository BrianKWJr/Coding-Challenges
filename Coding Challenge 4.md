function LongestWord(sen) { 
     senSplit = sen.split(" ");
  let LongestWord = sen[0];
  for(let i = 0; i < senSplit.length; i++) {
    if(senSplit[i].length >= LongestWord) {
      LongestWord = senSplit[i].length;
    }
  }
  return LongestWord;
  
}
   
// keep this function call here 
console.log(LongestWord(readline()));
