# Javascript Classes (Week 3 Day 1)

## What problem does using exports solve?

It helps with readability and performance, but importantly, it allows for scripts to be called across documents, without creating multiple "script" tags in the HTML DOM. This eliminates the HTTP requests created by that tag, which is slow and can impact performance.

## How does export differ from export default?

Export allows for multiple exported objects, while export default is reserved more for scripts that only need to deliver a single object.

## What is a benefit of using the Module System?

It improves readability, performance, and allows information to be delineated based on function so that the code remains both focused and modular.

Link: https://github.com/CyberTomB/animal-classes