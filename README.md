# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response
What is a function? The simplest way to define a function is to say it's a reusable block of code, where you can use it as many times as you need. Instead of rewriting your code and to call it over and over, we can use a function to do that for us. We can also do some mathematical solutions with functions where it takes an input and it will give us back an output.
such as: 1 + 1 as in put and it will give back the result of 2 as an output.

You can think of the function as a smoothie blender. Let's say you want to make a smoothie at home. You need fruits, other ingredients, and a blender to blend everything together. This is input, same as our function. We give our function a task to do for example to calculate 1 + 1.
Back to our smoothie, after we blend everything together, we get a smoothie. I can use the blender as many times as I want to make a smoothie without remaking a machine or getting another machine to get another smoothie. This is the same thing for our function the output we get form 1 + 1 is equals to 2, and I can put different input to find solution to different numbers without making a new function we just reusing it.

Here is an example of arrow function:
const myName = (firstName, LastName) => {
return `${firstName} + {LastName}`
};
First off we start an arrow function with a const variable. After that, we name our function. In this case, I named my function myName. Then we have an equal sign saying myName variable is equal to what comes after the equal sign, and we have a parameter (). Parameter takes our argument that we want to use inside of our function. We can have more than one argument inside of the parameter, we give it a task later to do it. Then we have our arrow which looks like this =>, it's another way to write our function in a shorter way, but if you see this after parameters it means it's a function.
Then we have curly braces {} this is where we write our function. In order for our function to work, we have to write it inside of curly braces. Inside of our function we then return our arguments, remember we said we are going to use our argument inside of our function. This is where we return our function to do something. Then, we tell it what to return.
Finally, we have to invoke it to print it so that way we will be able to see what we have done. In order to call the function, we print the name of our function followed by (). For example: I named my function myName, so we invoke myName(). We should get my first and my last name to the console. We have a this `` called backticks. We use backtick for string interpolation. This is used with a dollar sign $ followed by curly braces{}. Inside of our curly braces we can call our argument in the function directly.
///