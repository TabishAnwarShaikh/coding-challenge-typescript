# coding-challenge-typescript


Write a function in Typescript that uses generics to return the first non-repetitive character in a string. If no nonrepetitive char is found it should return a null. Please handle edge conditions - input and output.
// Example usage:
const result = firstNonRepeatingCharacter("aabbccddeeffg");
console.log("First non-repeating character:", result); // Output:
"g"
const result = firstNonRepeatingCharacter("abcabc");
console.log("First non-repeating character:", result); // Output:
null
