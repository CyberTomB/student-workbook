## What are the three main types of testing we can accomplish in Vue? What does each method provide?

Unit Testing, Component Testing, and End-to-End testing. Each method provides different layers of specificity, tools, and functional clarity. 

## What testing method do you think is the most useful? Why?

I think unit testing would be the most useful generally. While not always the most critical test for an application, the piece-by-piece nature of unit testing can help ensure working code from the ground up and isolate non-functional code to a high specificity.

## What testing method do you think is the least useful? Why?

End to End testing. Obviously there are going to be cases where E2E needs to be performed. However, it's not useful in the micro environment when new components or utilities are being added. It's best use case, as I understand it, is to determine full-scale functionality before live deployment.

