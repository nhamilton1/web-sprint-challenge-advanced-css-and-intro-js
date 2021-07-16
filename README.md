# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.


## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with.

### Commits

Commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe acessibility on the web to someone new to programming?

    Accessibilities on the web is an extremely important part, you want to give everyone the ability to view your website or application.
    Need to think about everyone whom might be accesssing your website or application and make sure they can consume the content. Maybe,
    the person is hard at hearing, so they need a screen reading, its best to use semantic HTML to help guide them. Another example, 
    maybe the person is coming from a part of the world where internet is slow and they don't have access to a computer, you might want
    to avoid using large images or compress them. 

2. Talk about 3 different things you can do to ensure your website is accessible. 

    First, you can use semantic HTML, making sure you are not using divs everywhere and that you are using the most semantic element as possible.
    Make sure you are defining the different parts of your web page. 
    
    Second, you would want to use scalable units for fonts. Font sizes that use %, or rem gives the site scalability. However, using fixed
    units of measure, such as pixels, does not give scalability. Using the scalable font will allow using to enlarge the text to make it
    easier for them to see. 

    Last, but not least, You will also want to make sure your h1h-h6 have meaning, because people might use screen readers to jump around based off those tags.
    Furthermore, this helps the user understand the structure and how your website is orginized. 


3. How would you explain the concept of a variable to someone new to programming?

    Variables are an extremely important part of programming, for this instance javaScript. Think of variables as a way to store values that you 
    can reference and/or retrieve later on in your program. 

    There are three ways to declare a variable in javascript: var, let, and const.
    3b. Var is an older way if declaring a varaible. Var can be can be redefined, redeclared, and is function scoped.
    3c. Let - cannot be redeclared, but it can be reassigned and is block scoped 
    3d. const - cannot be redeclared, cannot be reassigned, and is block scoped  


4. What is the purpose of using functions in code?

    A function is a block of code made to perform a task. A function will protect a block of code until they are invoked. Functions allow you to 
    store a piece of code that does a task inside of that block. When you want to you can just use a short command.  


5. How do you access a key inside of an object inside of an array?

    for example: const town = {
        name: 'Southold',
        attractions: 'beaches',
    }

    console.log(town.name);   // one way would be to use dot notation: this will go into town, then to name, and give southold back. 
    console.log(town['name']); //the other way is bracket notation. this is useful if you had keys with spaces in them

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [x] Ensure your website is responsive at 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.



## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

🦄 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-2-Study-Guide-16f656025c8744458addb068e6348101)


## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)


