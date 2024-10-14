## JavaScript Quiz Application

This is a simple JavaScript quiz application built with HTML, CSS, and JavaScript. The application presents a series of multiple-choice questions to the user, tracks their progress, and displays their final score.

### Files

* **quiz.html:** The main HTML file that defines the structure of the quiz application.
* **styles.css:** Contains the CSS styles for the quiz application, including layout, colors, fonts, and styling for different elements.
* **script.js:** Contains the JavaScript logic for the quiz, including question data, handling user input, updating the UI, and displaying results.

### HTML Structure (quiz.html)

1. **DOCTYPE Declaration:** Specifies the HTML version used.
2. **HTML Tag:** The root element of the HTML document.
3. **Head Section:**
    * **Meta Tags:**
        * `charset="UTF-8"`: Sets character encoding to UTF-8 for proper display of characters.
        * `viewport`: Sets the viewport for responsive design.
    * **Title:** Sets the title of the HTML page.
    * **Link Tag:** Links the `styles.css` file for external styling.
    * **Google Fonts:** Includes the Roboto font from Google Fonts.
4. **Body Section:**
    * **Main Container:**
        * **Heading:** Displays the title "JavaScript Quiz".
        * **Quiz Container:**
            * **Question Card:**
                * **Question Element:**  Displays the current question text (`id="question"`).
                * **Options Element:**  Displays the answer options (`id="options"`).
            * **Progress Bar:** Visualizes the progress through the quiz (`id="progress-bar"`).
            * **Next Button:** Allows the user to proceed to the next question (`id="next-btn"`).
        * **Result Container:**
            * **Result Heading:** Displays the user's final score (`id="score"`).
            * **Restart Button:** Allows the user to restart the quiz (`id="restart-btn"`).
    * **Script Tag:** Includes the `script.js` file for application logic.

### CSS Styling (styles.css)

* **General Styling:**
    * Sets basic font styles, font size, and colors.
    * Applies styles to the main container for layout and padding.
* **Quiz Container Styling:**
    * Centers the quiz container and sets its width.
    * Styles the question card, progress bar, and next button.
* **Question Card Styling:**
    * Sets styling for the question text and answer options.
    * Styles the answer buttons.
* **Progress Bar Styling:**
    * Defines the progress bar's appearance, including background color, height, and rounded corners.
* **Result Container Styling:**
    * Styles the result section, including heading and restart button.

### JavaScript Logic (script.js)

* **Question Data:** Defines an array of quiz questions, each containing the question text, answer options, and the correct answer.
* **Quiz Variables:** Initializes variables to track the current question index, score, and progress.
* **Display Question:** Function to render the current question and its options on the screen.
* **Check Answer:** Function to evaluate the user's selected answer and update the score accordingly.
* **Update Progress Bar:** Function to update the progress bar based on the current question index.
* **Next Question:** Function to move to the next question or display the results if all questions are answered.
* **Restart Quiz:** Function to reset the quiz and start over.
* **Event Listeners:**  Adds event listeners to the next button and answer options to handle user interactions.

### Functionality

1. The quiz starts by displaying the first question.
2. The user selects an answer option.
3. The selected answer is checked against the correct answer.
4. The score is updated, and the progress bar is advanced.
5. The next question is displayed, or the quiz ends and the results are shown.
6. The user can restart the quiz to take it again.

### How to Use

1. Save the HTML, CSS, and JavaScript files in the same directory.
2. Open the `quiz.html` file in a web browser.

This README provides a basic overview of the JavaScript Quiz application. You can customize the questions, styles, and functionality to create your own unique quiz.
