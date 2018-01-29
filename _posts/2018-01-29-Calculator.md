---
title: Calculator
layout: post
author: guy.lane
permalink: /calculator/
source-id: 12RVNsrMo3f9QALRvJwhlmSJYivnkamv1vfWbw8xZps0
published: true
---
Calculator

We have been working on another worksheet to make a calculator, firstly you type your first number in, then your second. Once you have done that it will provide you with 4 different options you can do to those numbers, they are (1) add, (2) multiply, (3) subtract, (4) divide. So far my coding has worked until the point where one has to add, multiply, subtract or divide. As we have been moving on fast with our coding subject i don't have much time i n lesson to fix it, but at home i might try and solve my problem.

def add(num1,num2):

    answer = num1 + num2

    return answer

    

def Multiply(num1,num2):

    answer = num1 + num2

    return answer

    

def Subtract(num1,num2):

    answer = num1 + num2

    return answer

    

def Divide(num1,num2):

    answer = num1 + num2

    return answer    

first = int(input("Enter your first number: "))

second = int(input("Enter your second number: "))

print("Choose an option: (1) Add, (2) Subtract, (3) Divide, (4) Multiply")

choice= int(input())

answered = 0

while (answered != 1):

 if  choice == 1:

     answer = add(first,second)

 elif choice == 2:

     amswer = Subtract(first, second)

 elif choice == 3:

     answer = Divide(first, second)

 elif choice == 4:

     answer = Multiply(first, second)

 else:

  print("Select an available answer")

print("The answer is",answer)

