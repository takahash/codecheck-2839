# Look and Say!

This challenge is to make a function which returns a number according to some secret rule.

If this function receives '1', it returns '1'.   
If it receives '2', it returns '11'.  
If it receives from '3'  to '7', it returns the following results, respectively,

```
1 -> 1
2 -> 11
3 -> 21
4 -> 1211
5 -> 111221
6 -> 312211
7 -> 13112221
```

Find the rule of this sequence and implement the function.

## How to implement
You can use the following languages to solve this challenge.

- NodeJS
- Ruby
- Python3
- Go
- Java

We want you to make it as a CLI application.  
Input parameter will be passed as an argument of CLI.  
Output should be written to stdout.

How to make CLI application with selected language is written in [LANGUAGE].md

## Secret Test
You can see 7 testcases in [testcase.js](test/testcase.js)  
However, this challenge has more 3 testcases. These are hidden.

- Secret1. Pass '8' to this function, it should return collect answer.
- Secret2. Pass '20' to this function, it should return collect answer.
- Secret3. If the input number is '10000', what is the initial 500 digit of result? Write the answer at the top line of [answer.md](answer.md). Also, explain how to solve this problem below.

If your function is implemented correctly, first 2 test will pass.

However, if your function is implemented in a very simple way, the last question eat all your memory.  
Try to find some optimization.

Note. 
The secret tests will run on submitting challenge.
These results are never shown on WebEditor.
