# Working in MVC with Complex Data and Array Methods (Week 3 Day 4)

## What problems does the Observer Pattern seek to solve?

The problem is that it can be hard to keep multiple page elements synced with entered data without creating a laundry list of dependencies and other undesireable complexity. The Observer Pattern streamlines the process that allows us to update the DOM when events are created by user input.

## What are the three mechanisms of the observer pattern?

The Subscribe method, the Unsubscribe method, and the Broadcast method.

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

The EventEmitter object in the "Utils" of the BCW Template provides the methods needed to process events, identifying when information is affected on the DOM and enables instantaneous client-side updates.