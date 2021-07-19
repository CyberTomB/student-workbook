# Encapsulation (Week 3 Day 2)

## What is the purpose of Encapsulation?

The purpose of encapsulation is to privatize the data being manipulated such that only the desired methods can interact with that state.

## What were some of the problems with closures and the underscore prefix?

The underscore prefix is a convention, and not necessarily a true privitization of the method. Encapsulation can actually ensure the method is private with relation to the user.

## How do we create private variables in a ES6 Class? Why would you do this?

In order to improve both security and functionality, we can use encapsulation (via classes) to keep methods from being accessed by users (and thereby also bad actors). Some functions might affect data in ways we may need strict parameters for, and allowing users direct access could create undesirable data losses or exposure.

Project Link: https://github.com/CyberTomB/vending-machine