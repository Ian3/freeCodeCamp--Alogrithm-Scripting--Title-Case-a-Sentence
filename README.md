# freeCodeCamp--Alogrithm-Scripting--Title-Case-a-Sentence

CHALLENGE
Return the provided string with the first letter of each word capitalized. Make sure the rest of the word is in lower case.


SETUP
function titleCase(str) {
  return str;
}

titleCase("I'm a little tea pot");


MY SOLUTIOIN
function titleCase(str) {
  return str.toLowerCase().split(" ").map(function(x) {let a = x[0].toUpperCase(); let b = x.slice(1); return a+b}).join(" ");
}
console.log(titleCase("I'm a little tea pot"));
