---
keywords: fastai
description: Code.
title: Tri 1 Corrections
toc: true 
badges: true
comments: true
categories: [jupyter]
image: images/chart-preview.png
nb_path: _notebooks/2022-09-8-Youtube-Channel.ipynb
layout: post
---
# Tri 1 Corrections

![]({{site.baseurl}}/images/1.png "https://github.com/fastai/fastpages") 

Which of the following is the most appropriate documentation to appear with the printNums procedure?

A
Prints all positive even integers that are less than or equal to max.

B
Prints all positive odd integers that are less than or equal to max.

C
Prints all positive even integers that are greater than max.

D
Prints all positive odd integers that are greater than max.

Corrections: I put A and the correct answer is B. The reason for this as put from collegeboard, "The procedure initializes count to 1. Inside the loop, the value of count is displayed, then count is incremented by 2 to the next odd integer. The loop terminates when count exceeds max, so all positive odd integers less than or equal to max are printed.".  The function starts at 1 and adds two, and all the numbers are positive so therefore they are all odd and positive integers and the count has to be less then the max so the only plausible answer is B. 

![]({{site.baseurl}}/images/2.png "https://github.com/fastai/fastpages")

Corrections: I but D and it is wrong because " The procedure does not interchange the values of j and k. Rather, it returns a new list with the values at indices j and k interchanged."
 This means that this,:
 newList[j] ← numList[k]

newList[k] ← numList[j]

Does not mean they are interchanged but instead the values at indices j and k are interchanged. The right answer is B because college board says, "The procedure creates a copy of numList called newList. The element at newList[j] is assigned the element at numList[k], and the element at newList[k] is assigned the element at numList[j]. Therefore, the difference between numList and newList is that the elements at indices j and k are interchanged. The procedure only works if j and k are valid list indices, so it is important to document that j and k are both between 1 and LENGTH(numList), inclusive.". I now understand what the function is. 

![]({{site.baseurl}}/images/3.png "https://github.com/fastai/fastpages")

What I got wrong: Collegeboard says, "The Internet was not designed to be completely secure. The protocols used on the Internet do not ensure that all communications are secure." This means that open protocols and the internet in general was not created to be secure and instead have a different purpose. 

Correction: Answer D is correct because collegeboard says, "Protocols are agreed-upon sets of rules that specify the behavior of a system. Protocols used on the Internet enable devices from different manufacturers to communicate in a standard way." This means the use of open protocols are for their to be an open connection between devices via the internet. 

![]({{site.baseurl}}/images/4.png "https://github.com/fastai/fastpages")


What I did wrong: I put A and it is wrong because according to Collegeboard, "Statement II is true because colors can be encoded as sequences of bits. Statement III is true because sequences of bits can be used to represent sound." This basicly just means that I thought binary did not have the capabilities that I thought because it can be used to ehelp encode colors as sequences of bits and for sound as well.

Correction: Answer is D because Binary can do all of these capablities. According to collegeboard, " All digital data is represented at the lowest level as sequences of bits. Statement I is true because strings of characters can be represented by sequences of bits. Statement II is true because colors can be encoded as sequences of bits. Statement III is true because sequences of bits can be used to represent sound." This means that binary can do much more then I thought. 

![]({{site.baseurl}}/images/5.png "https://github.com/fastai/fastpages")

What I did wrong: I put B and it is wrong according to collegeboard because, "Binary 1011 is equivalent to decimal 11 and should be placed before decimal 12." This is wrong because decimal 12 is greater then binary 1101 since it is 11.

Corrections: The answer is A because sccording to collegeboard, "Binary 1011 is equivalent to 2^3+2^1+2^0, or decimal 11, and binary 1101 is equivalent to 2^3+2^2+2^0, or decimal 13. The order of the numbers (written in their equivalent decimal format) is 5, 11, 12, 13." I learned more about the numerical values that are associated with binary now. 

![]({{site.baseurl}}/images/6.png "https://github.com/fastai/fastpages")

What I did wrong: I put D and it is wrong because according to collegeboard, "Instead of using a numeric variable to represent whether the student is absent, it would be more appropriate to use a Boolean variable because the status could be represented using only the values true and false." This is wrong because a Boolean variable can be defined as it either happens or not which is true or false. 

Corrections: The answer is C because according to collegeboard, "A student name is best represented using a string. The status of whether a student is absent can be represented using only the values true and false, so a Boolean variable is most appropriate. For both variables, using meaningful variable names helps with the readability of the code segment." You use true false logic because it either means they are false or not false. 

![]({{site.baseurl}}/images/7.png "https://github.com/fastai/fastpages")

What I did wrong: According to Collegeboard it is not C because,"Using a list does not prevent a program from changing the value of a variable." This means what I put is simply not true because I did not understand the nature of a list. 

Corrections: The correct answer is B because according to collegeboard, "Using a list as a data abstraction can result in a program that is easier to develop and maintain. It is easier to apply the same algorithm to every element in a list than to apply the same algorithm to many separate variables." This shows how a list can help easily develop and maintain as a data abstraction of a program.

 ![]({{site.baseurl}}/images/8.png "https://github.com/fastai/fastpages")

 What I did wrong: 
The character "e" is the character at index 2 of the string element at index 2 in wordList. This is wrong because it is clearly not index 3 of the wordlist. 

 Corrections: According to collegeboard the answer is C because "The element at index 3 in wordList is "ghi". The character at index 2 of "ghi" is "h"." No explanation when reading it, it makes perfect sense in retrospect. 
 

![]({{site.baseurl}}/images/9.png "https://github.com/fastai/fastpages")

What I did wrong: I selected answer B but it is wrong because according to collegeboard, "The last assignment statement assigns a copy of myList to yourList, so the contents of yourList are changed." So therefore it is the opposite of what I actually did.

Correction: According to collegeboard, "The last assignment statement assigns a copy of myList to yourList. Since myList contains [10, 30, 50, 70], yourList will also contain [10, 30, 50, 70]." which basically means that due to the function your list will also have the odd numbers so it is therefore A. 

![]({{site.baseurl}}/images/10.png "https://github.com/fastai/fastpages")

What I did wrong: I put C but according to collegeboard, it id wrong because, "This code segment assigns maxPS the value 50 when time > 120 and assigns maxPS the value 30 otherwise." This basically means 120 was not put in the right order because the if-else statement was wrong. 30 and 50 should be switched. 

Correction: The correct answer is D and collegeboard says, "This code segment uses the IF statement to set maxPS to 30 when time > 120 and uses the ELSE statement to set maxPS to 50 otherwise." This makes more sense because 50 should come after the else statement. 

![]({{site.baseurl}}/images/11.png "https://github.com/fastai/fastpages")

Corrections: According to collegeboard, " The first three statements assign values to the variables. Since num1 < num2 evaluates to false, the body of the ELSE block is executed and num3 is assigned the value 4. Since num2 ≥ num3 evaluates to true, the body of the second IF block is executed and num1 is assigned the value 8. Lastly, sum is assigned the value of 8 + 4 + 4, or 16." I instead did 8 + 4 and just that. I forgot to include the other 4. 

![]({{site.baseurl}}/images/12.png "https://github.com/fastai/fastpages")

What I did wrong: It is clear when reading "The code segment iterates through each element in the list, incrementing count1 for each positive value and incrementing count2 otherwise. There are only two positive values in the list, not five." that the values I picked did not match up. 

Corrections: According to collegeboard, "The code segment iterates through each element in the list, incrementing count1 for each positive value and incrementing count2 otherwise. The list contains two positive values, so count1 is 2 and count2 is 3." This makes a lot more sense when you look at the coding.

![]({{site.baseurl}}/images/13.png "https://github.com/fastai/fastpages")

Corrections: C is clearly the only option correct because according to collegeboard, "The first three statements assign values to the variables. The fourth statement assigns the value of y (which is 50) to x. The fifth statement assigns the value of z (which is 75) to y. The sixth statement assigns the value of x (which is 50) to z. Therefore, x and z both have the value 50." When the statement is executed, the top line of Y points to x which has a value of 25 which therefore puts the number under 50. 


![]({{site.baseurl}}/images/14.png "https://github.com/fastai/fastpages")

Corrections: The Answer I put was B because I had no idea what to do, but the answer is A because according to collegeboard, "This statement will correctly form the initials. It uses calls to prefix to obtain the first letters of each name, then uses a call to concat to concatenate the two letters in the correct order." This now helps me understand how to cormat initials and names. 