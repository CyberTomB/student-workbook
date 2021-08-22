# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This file provides metadata to NPM and handle your project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
In the root directory of the application. This is in order to ensure proper placement of depenencies and other files that might reference the package file.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
ENV files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
From the "logs" page in herokuapp, or from your debugger console.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Assuming your herokuapp is set to auto-deploy, simply update the correct branch from your github.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
By using branches, you can keep working versions of your application intact and deployed, while continuing to update and refactor the code on other branches.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Anytime a pull request is made that would push to the deployed branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging.
```
