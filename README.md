# Pharmacure

## Overview

Pharmacure is a web application that is connected to a database and whenever a user gives an input it sends a query to the database gets a required solution and gives it to the user as output. It also gives latest information about medical field to the users. Users can also buy medicines and other medical related stuff in this website. This website is compatible in all devices.
Generally, due to busy lives people often neglect to visit a doctor for minor health issues like cold, cough, fever which may lead to serious diseases in future.This problem can be effectively solved by providing virtual assistance to users which behaves exactly like a doctor. This saves time and energy for people as everything is possible by clicking in your device instead of reaching a doctor.

## Motivation

The main purpose of this project is to save time for the people. As we know every individual is busy with their works and neglect small health issues which may lead to serious problems in future. So, we came up with an idea of providing a virtual health assistance to the people through our website. This website does not contain any doctor but it can give suggestions and precautions according to your symptoms same like how a doctor suggests. This website also educates people with latest information related to medical field and diseases. And this also allows people to buy medicines.


## What does this website do?

The proposed project “Pharmacure” is mainly based on providing suggestions to the user by taking symptoms as input. Generally, it takes the symptoms and medical history (which was provided by the user during registering) as input, sends a query to the database which was linked with our website and selects an appropriate result and sends it  to the user as output. By this way it will be useful for a person to know the disease by sitting in home.
 This website also provides user with latest information related to medical field. Alert news can also be seen scrolling in each webpage of our website. Users can change in settings if they do not want alert news. But this scroll is provided by default to every user.
This website also provides an option for the users to buy medicines. Users are provided with multiple modes of payment like credit/debit and cash on delivery. Users are provided with a unique track Id when they order, using this track Id he/she can track their order until their shipment is reached.

![](images/flowchart.PNG)

## Medicine Suggesting Module

This module focuses on suggesting a medicine according to the symptoms given by the user. It gives suggestions keeping medical history, blood group, age in track. It also suggests dosages according to age and allergies. Information of every user is stored with the help of a database which is linked to the website. When a user types a symptom the website sends a query to the database, database will verify all the records and send an output to the user

## Purchase Module

After getting suggestions in medicine module, users can buy medicines directly in the website. Or else users can buy medicines that are suggested or can buy on their own. After adding items to the cart there will be a option as proceed further. If the user clicks it, the web page leads to a payment portal. The user has many options for mode of payment like credit/debit, cash on delivery. After completing all procedures and the user clicks checkout button then the order will be confirmed. 
The user receives a confirmation mail or a message to the given contact number with the track Id and order details. The user can use the track Id and check where is his/her shipment until it is delivered to them. Every order creates a unique track Id which will be available only to that user. Once the order is delivered again the user gets a mail that the order is received.

## News/Notification Module
Once the user enters the website he will get a popup of latest news. This is a default setting, if user don’t need a popup he/she can change in settings. If the user disables this feature then he can see news in a block at left side. Alert news can be seen scrolling in all web pages of the website. User also gets news in notification bar of their devices. When a user orders he/she will get notifications of the status of their shipment. The website also warns if the user is trying to buy medicines which are not suitable for his age.

## Conclusion

Therefore, Pharmacure website takes input from the user like age, blood group, past medical history while registering and keeps a track of it throughout the events. When user enters symptoms, a query is passed to the database requesting an appropriate result. User can even purchase medicines and can have the track of shipment till the end. These tracking is possible by a unique tracking ID which we provide. Users can also get update on latest medical information going on around the world.


