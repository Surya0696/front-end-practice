//Q1. To reverse a string in JavaScript without using built-in methods

// var txt = "hi how are you";

// function makeReverse(ele) {
// let reversed = "";
// for (let i = ele.length - 1; i >= 0; i--) {
// reversed += ele[i];
// }
// return reversed;
// }

// console.log(makeReverse(txt));

// ------------------------------------------------------------------------------------------------------------

// Q2. Palindrome or Not ?

// var str = "Level";

// function checkPalindrome(checkStr) {
// let reversed = "";

// for (let i = checkStr.length - 1; i >= 0; i--) {
// reversed += checkStr[i];
// }
// return reversed === checkStr;
// }

// console.log(checkPalindrome(str));

// ------------------------------------------------------------------------------------------------------------

// Q3. how to find out each letter count?

// var countTxt = "banana";

// function countLetters(str) {
// const count = {};

// for (let i = 0; i < str.length; i++) {
// const howMuch = str[i];

// if (howMuch === " ") continue; // Skip spaces

// if (count[howMuch]) {
// count[howMuch]++;
// } else {
// count[howMuch] = 1;
// }
// }

// return count;
// }

// console.log(countLetters(countTxt));

// ------------------------------------------------------------------------------------------------------------

// Q4. find the longest word in a sentence ?

// var str = "I am learning JavaScript programming";

// function checkLongestWord(elem) {
// var word = elem.split(" ");
// var longest = "";
// word.forEach((words) => {
// if (words.length > longest.length) {
// longest = words;
// }
// });
// return longest;
// }

// console.log(checkLongestWord(str));

// --------------------------------------------------------------------------------------------
// Q5. find the most frequent (repeating) word in a string.

// function mostFrequentWord(str) {
// const words = str.split(" ");
// const freq = {};
// let maxWord = "", max = 0;

// for (let word of words) {
// freq[word] = (freq[word] || 0) + 1;
// if (freq[word] > max) {
// max = freq[word];
// maxWord = word;
// }
// }

// return maxWord;
// }

// console.log(mostFrequentWord("the was one boy in office that boy very good boy"));
// Output: "boy"

// ------------------------------------------------------------------------------------------------------------------------------------------------------

// Q6. removes a duplicate numbers correctly?

// var num = [1, 2, 2, 3, 4, 4, 5];

// function removeDpNum(ele) {
// const DpNum = [];

// for (let i = 0; i < ele.length; i++) {
// if (!DpNum.includes(ele[i])) {
// DpNum.push(ele[i]);
// }
// }

// return DpNum;
// }

// console.log(removeDpNum(num));

//--------------------------------------------------------------------------------------------------------------

//Q7. make it duplication ?

// function strduplication(str) {
// let result = "";

// for (let i = 0; i < str.length; i++) {
// result += str[i]; // add each charr once
// }

// for (let i = 0; i < str.length; i++) {
// result += str[i]; // add each charr again
// }

// return result;
// }

// console.log(strduplication("surya11")); // Output: "surya11surya11"

// -----------------------------------------------------------------------------------------------------------------------------

//Q8. add all the numbers in the array [1, 2, 3, 4, 5, 6] using JavaScript.

// var numbers = [1, 2, 3, 4, 5, 6];

// function addAll(arr) {
// let sum = 0;
// for (let i = 0; i < arr.length; i++) {
// sum += arr[i];
// }
// return sum;
// }

// console.log(addAll(numbers)); // Output: 21
