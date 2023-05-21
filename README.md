# Math Quiz Game

This is a simple math quiz game implemented using JavaScript. It generates random multiplication questions and allows users to submit their answers. The game keeps track of the user's score using local storage.

## Usage

To play the math quiz game, follow these steps:

1. Open the `index.html` file in a web browser.
2. The game will display a question asking for the result of multiplying two random numbers between 1 and 10.
3. Enter your answer in the input field and submit the form.
4. If your answer is correct, your score will increase by 1. Otherwise, your score will decrease by 1.
5. The score is displayed on the page, and it will persist even if you close and reopen the game.

## Code Explanation

The JavaScript code provided creates a math quiz game using the following steps:

1. Two random numbers between 1 and 10 are generated using `Math.random()` and `Math.ceil()`.
2. The question and score elements are selected from the HTML using `document.getElementById()`.
3. The current score is retrieved from the local storage. If no score exists, it is initialized to 0.
4. The question and score are displayed on the page.
5. An event listener is added to the form element, which listens for form submissions.
6. When the form is submitted, the user's answer is extracted from the input field and converted to a number.
7. If the user's answer is correct, the score is incremented and updated in the local storage. Otherwise, the score is decremented.
8. The local storage is updated using the `localStorage.setItem()` method.

