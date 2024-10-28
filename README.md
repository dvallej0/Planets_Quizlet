This project is a planet-themed quiz application designed to test users on their knowledge of planets within and beyond our solar system. Here's a breakdown of its functionality and structure:

Project Components
HTML Structure:

The HTML provides a basic structure for the quiz, with placeholders for dynamic content:
A main container (<div id="container">) holds all quiz elements.
The question text, score, and image are initially populated with placeholder values, which JavaScript updates.
Buttons represent the answer choices and user actions (Check Answer and Next >>).
The <div id="completed"> shows a completion message when all questions are answered.
CSS Styling:

Styles are applied for a visually appealing layout:
The body has a background image of the Milky Way, enhancing the space theme, and the quiz area uses contrasting colors.
.questionWrapper and .choice-div elements manage alignment and padding.
Answer choice buttons are styled with specific colors to indicate correct (green), incorrect (red), and selected (gray) options.
The completion message uses absolute positioning and overlay styling for prominence.
JavaScript Logic:

The Quiz.js file powers the quiz’s interactivity:
Quiz Data: An array of planet objects, each with an image URL and the correct answer.
Event Listeners: Attached to answer choices, Check Answer, and Next buttons to handle user input.
Question Management: getQuestion() populates the current question, shuffles answer choices, and updates the question counter.
Answer Checking: When Check Answer is clicked, it checks if the selected answer matches the correct answer, highlights the choice, and updates the score.
Completion Handling: Once all questions are answered, the completion message is displayed and the Next button is disabled.
User Experience Enhancements:

The shuffle function (shuffleArray) ensures each question and choice order is random.
Answer choices are highlighted to indicate the selected and correct/incorrect options, helping users visually track their choices.
The quiz is completed with a congratulatory message that overlays the screen once all questions are answered.
This setup provides an interactive and engaging experience for users learning about different planets. Let me know if you need further customization or additional functionality for this project!











ChatGPT can make mistakes. Check important info.
