# Instructions

To get a user input, we have to use the prompt function

## Steps

Create a variable answer and assign to function prompt with question 'What is 1 + 1? '
```javascript
const answer = prompt('What is 1 + 1? ');
```
Next, add a console.log function with the answer in it
```javascript
const answer = prompt('What is 1 + 1? ');
console.log(answer);
```
Click on the run button, and you should see in the console:
```
What is 1 + 1?
```
Use your mouse/touchpad and click on the `>`. Type `2` and press enter.

![demo](assets/demo.gif)

You noticed that we did not print immediately of any value. This is because prompt function stops all the code below as it awaits for the user input.

<details>
<summary>Full code</summary>

```javascript
const answer = prompt('What is 1 + 1? ');
console.log(answer);
```
</details>