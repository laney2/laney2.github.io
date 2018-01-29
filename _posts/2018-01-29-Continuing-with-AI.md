---
title: Continuing with AI
layout: post
author: guy.lane
permalink: /continuing-with-ai/
source-id: 1kcgLkw5_bw1BLvLJyzCtuIdsq-YXXLB0pjy9zU5IsZA
published: true
---
Continuing with AI

My progress in Ai has excelled as i now have a few question which i can answer and get an answer back: 

a=input("Hello, what is your name?")

print("hi," + a + ".")

b=input("Have you had a good day? (yes or no)")

if b.lower() == "yes":

  print("Thats nice to know " + b + ".")

elif b.lower() == "no":

  print("It can't be that bad")

  

else:

  print("I do not understand")

c=input("What are your plans for the weakend?")

print("Have fun doing " + c + ".")

d=input("What is your favorite sport?")

print("Cool, mine's basketball")

e=input("Do you like tea or coffee? (tea or coffee)")

if b.lower() == "tea":

  print("Same")

  

elif b.lower() == "coffee":  

  print("I don't like the taste")

  

else:

  print("I have never had that drink, what does it taste of?")

  

  f=input("Do you get pocketmoney?")

  print("ok does it work ike this, ")

  pocketMoney = 0.01

  

totalMoney=0

for week in range(1, 27):

 print("\nIt is week",week)

 print("You will get £ ",pocketMoney)

totalMoney=totalMoney + pocketMoney

pocketMoney=pocketMoney*2

input("\nPress ENTER to exit program")

print ("total money is ", totalMoney)

  

So far i have asked a few questions which the ai will respond to if i type in an answer, e.g: "Do you drink apple juice", if i typed “yes” it would respond with “ok” however if i responded with “csgjds” it will say “sorry, i don't understand”. I hope to improve it in the future. And i feel like i can add some more complex things for it to do.

