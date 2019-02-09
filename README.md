# WeCode Berlin

## Introduction

Hello world! Welcome to the lab where you will create and deploy online your own CV website! You can find a demo just here: https://maxence.netlify.com

To start, you can download the ZIP accessible here: .........................

If you need any help during this exercise, feel free to ask the help of one of the teacher in the class 😀

Let's go 💻🚀


## Iteration 1 | HTML and CSS | Design your CV Website

From the `index.html` and `style.css` you've downloaded, you already have a working website. 

The goal of this iteration is to update the HTML and CSS to fit your identity!

Start simple by editing the HTML and writing your own experience and education.

Then change some parameters of the CSS, such as the color.

After that, it's up to you to customize your own CV website!

## Iteration 2 | Pure JavaScript | Select a random element in an array

The goal is to create a function `randomElement` that takes an array as parameter and returns a random value.

**Example**:
```js
var arr = ['a','b','c','d','e'];
console.log(randomElement(arr)); // => 'c'
console.log(randomElement(arr)); // => 'e'
console.log(randomElement(arr)); // => 'c'
```

For this, you will have to use:
- [`Math.floor()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor)
- [`Math.random()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

## Iteration 3 | DOM Manipulation | Display a random joke on the page

Now the goal is to link the JavaScript with the CV website! Everytime the user clicks on 1 of the 2 buttons ("*Yes!*" or "*No*"), a message will be displayed on the page.

For that, create a `main.js` and import it in the end of your `index.html` file.

```html
<!-- index.html -->

<!-- ... -->

  <!-- Import of main.js -->
  <script src="main.js"></script>
</body>
</html>
```

Then, you have to create a file `main.js`

```js
console.log("main.js file is loaded!");

// Source of the jokes: http://www.icndb.com/the-jokes-2/
var jokes = [
  "When Chuck Norris goes to donate blood, he declines the syringe, and instead requests a hand gun and a bucket.",
  "Chuck Norris can divide by zero.",
  "It takes Chuck Norris 20 minutes to watch 60 minutes."
];

document.querySelector('#yes').onclick = function () {
  // TODO: write the code of the function
  // You will have to use: document.querySelector(mySelector).innerHTML = "My new HTML"
  console.log("Yes was clicked");
}

document.querySelector('#no').onclick = function () {
  // TODO: write the code of the function
  // You will have to use: document.querySelector(mySelector).innerHTML = "My new HTML"
  console.log("No was clicked");
}
```

Now, write the JavaScript to display a message on the page, for example a joke, on buttons clicks.

If you managed to finish, you can:
- Make sure you cannot have 2 jokes at the same time.

## Resources
- To understand what is CSS Flexbox: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- To practise Flexbox: https://flexboxfroggy.com/
- https://www.flaticon.com/
- To learn the basics of JavaScript: https://mc100s.gitbooks.io/javascript/content/