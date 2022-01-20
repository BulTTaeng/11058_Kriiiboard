# 11058_Kriiiboard

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/11058_Kriiiboard/blob/main/11058_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

There is 2 option to make max A.

1. press ctrl-V if we have something in the buffer.

2. press ctrl-A ctrl-C ctrl-V in final 3 steps.

Just pressing A is not an option because it is better to press it before and put in a buffer.

To do option 2, we need 3 steps. After we press ctrl-A ctrl-C , we can press ctrl-V as much as we want. 

So, find the max value in (current - 3) and do option 2 and in (current - 4) can do option 2 and press ctrl-V one more time .... and goes on.

After that, starting from (current -1) and if it have buffer, do option 1 will be ((current - 1)'s buffer ) * 2 , ((current - 2)'s buffer ) * 3 .. and goes on.

The max value in above is the answer.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
