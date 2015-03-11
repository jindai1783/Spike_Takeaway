# Spike Takeaway

## Introduction

TopDown is typically BreadthFirst, but a Spike is DepthFirst. From the top to the bottom, then CloseTheLoop. So-called because a spike is "end to end, but very thin", like driving a spike all the way through a log.

This repository is a spike version of my attempt to Makers Academy's Takeaway challenge. A fully functional TDD version can be found at [Takeaway].

[Takeaway]: https://github.com/jindai1783/Takeaway

## Task

* Write a Takeaway program.
* Implement the following functionality:
* list of dishes with prices
* placing the order by giving the list of dishes, their quantities and a number that should be the exact * total. If the sum is not correct the method should raise an error, otherwise the customer is sent a text * saying that the order was placed successfully and that it will be delivered 1 hour from now, e.g. "Thank * you! Your order was placed and will be delivered before 18:52".
* The text sending functionality should be implemented using Twilio API. You'll need to register for it. * It’s free.
* Use twilio-ruby gem to access the API
* Use a Gemfile to manage your gems
* Make sure that your Takeaway is thoroughly tested and that you use mocks and/or stubs, as necessary to * not to send texts when your tests are run
* However, if your Takeaway is loaded into IRB and the order is placed, the text should actually be sent
* A free account on Twilio will only allow you to send texts to "verified" numbers. Use your mobile phone * number, don't worry about the customer's mobile phone.
* Note: We are looking for good OO design and programming! Remember the SOLID principles!