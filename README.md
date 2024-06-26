# DAY-12

Problem Statement

Given a string should ignore all special characters & consister if the obtained alphanumeric string is palindrome or not.

Input: s = "A man, a plan, a canal: Panama"

Output: true

Explanation: "amanaplanacanalpanama" is a palindrome.

Solution Approach 

Simply take all alphabets & numbers into a string ,copy it into temp string & reverse the string.If reversed string & original string are same return true else false.
Can use "isalnum()" function to take numbers,alphabet characters into string or can set conditions in if statements. 
