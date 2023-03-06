# CBC Week 04 Challenge: Science Quiz
## Description

This project is the fourth challenge from the coding bootcamp from UC Berkeley.  The challenge was to create a quiz with the following requirements:

- When the user clicks the start button, a timer will start and the user will be presented with a question.
- When the user answers a question, they will be presented with another question.
- When the user answers a question incorrectly, time will be subtracted from the clock.
- When all questions are answered or the timer reaches 0, the quiz is over.
- When the quiz is over, the user can save their initials and score.  The scores will be saved in local storage.
  
The theme of the quiz and extra quality of life features were added by me.  The quiz theme is natural science, because it is my favorite topic to learn about.  The extra features that I added include:
- A reset button that will reset the quiz to the beginning.
- A view high scores button that will show the high scores.
- A clear high scores button that will clear the high scores from local storage.

The purpose of this assignment was to practice using Javascript to manipulate the DOM and to practice using local storage.  I used query selectors to select elements in the DOM and then used event listeners to listen for events on those elements.  The event listeners then called functions that would manipulate the DOM.  I used local storage to save the high scores.  This required me to convert the high scores to a string and then save the string to local storage.  I also had to convert the string back to an array of objects when I wanted to use the high scores.

## Usage

The quiz is a multiple choice quiz.  The user will be presented with a question and four possible answers.  The user will click on the answer they think is correct.  If the answer is correct, the scoreboard will flash green.  If the answer is incorrect, 15 seconds will be subtracted from the timer and the scoreboard will flash red.  When the user has answered all the questions or the timer reaches 0, the quiz will end.  The user will be able to enter their initials and save their score.  The user can also view the high scores or clear the high scores.

- To begin the quiz, click the start button.  The timer will start and the first question will appear.

- If you answer incorrectly, 15 seconds will be subtracted from the timer and the scoreboard will flash red.  If you answer correctly, the scoreboard will flash green.  When you have answered all the questions or the timer reaches 0, the quiz will end.

- You will be able to enter your initials and save your score.  You can also view the high scores or clear the high scores.

- Clicking the View Highscores button will show the high scores.  Clicking this at any time will stop the quiz.

- Clicking the Clear HighsScores button will clear the high scores from local storage.

- Clicking the Reset button will reset the quiz to the beginning.

## Mock Up

The mock up below was provided in the bootcamp homework materials.  We were to create our our HTML, CSS, and JS so the final product does not look the same as the mockup, but it has much of the same functionality and flow.  

<p align="center"><img src="./assets/images/04-web-apis-homework-demo.gif?raw=true" alt="Mock up gif"/></p>

## Final Product

The final product is a quiz about natural science.  It is deployed at https://jdempe.github.io/bootcamp-04-science-quiz/.  The screenshot below is of the homepage when it is first loaded.  From this page, the user can start the quiz or look at high scores.

<p align="center"><img src="./assets/images/04-science-quiz-screenshot.png?raw=true" alt="Final product screenshot"/></p>

## Credits

### Resources

The below resources contributed to the project.

- [W3 Schools](https://www.w3schools.com/js/default.asp) provides great tutorials on many Javascript methods.

- [Font Space](https://www.fontspace.com/category/science) has many free fonts available.  I used the CASANOVA SCOTIA font.

- [Vecteezy](https://www.vecteezy.com/free-vector/science-background) has many free backgrounds.  I used one of the free science themed backgrounds.
  
- [Ian Lunn](https://github.com/IanLunn) created an awesome library called [Hover.css](https://twitter.com/davidmacd) that adds some plug and play css animation classes.  I used this for some of the moving icons on my page.

- [Coding Beauty](https://codingbeautydev.com/blog/javascript-check-if-string-contains-only-letters-and-numbers/) has a tutorial on how to check if a string contains only letters.  This was used to confirm that the user entered only letters when they entered their initials.
  
### Collaborators

On this project, there was no peer review.

## License

Refer to the LICENSE in the repository.

## How to Contribute

Contribute at https://github.com/JDempe/bootcamp-04-science-quiz