---
layout: essay
type: essay
title: Do Yourself A Favor
date: 2021-02-11
labels:
- Coding Standards
- Improvement

---

Coding Standards. You hate them or you love them, but they do make a difference, especially in this world. 

## Learning How To Code
When I was first learning how to code, my professor told us the importance of coding standards. I had no idea, because I was taught immediately using coding standards. It truly made my code look neat and easy to read. I thought everyone followed coding standards because using programs like Eclipse and Visual Studio Code, you can select your whole code and press format and it will format your code to make it easier to read. Coding Standards are like the rules your parents have, you might think they are ridiculous, but they are there for a reason. It is not just to make your code look "pretty", it is really beneficial. When learning how to code, it is easier to trace when your code follows a format. When you are first learning about loops and have a couple for loops inside a while loop it becomes complicated. Coding standards help to find that semantic error much quicker than if you wrote your code like a big mess with no indents or spacing. We all know semantic errors are the worst and hardest kind to debug. A computer can not tell you where your problem is, you have to find it yourself, and staring at your code in a big mess does not make it any easier. 
### Example 1
```
let num = 0;
for (int i = 0; i < 3; i++) {
  num += i;
  i++
}
return num;
```
### Example 2
let num=0;
for(int =0;i<3;i++){num+=1;i++}return num;

I have made the same simple syntax error in both codes. You tell me which one is easier to read. 

## ESLint
ESLint is a stricter coding standard to follow, but it allows all code to look uniform. Offering suggestions how to fix the errors is very helpful to learn Javascript and keep neat code. It is hard to keep different coding languages and their certain rules in mind. ESLint will catch those errors and have suggestions to fix them. It is a little difficult using Underscore, because with ESLint you have to run your code in Google to see the console and the output, but overall it is worth it to be able to get the green check mark and have errors highlighted. 
