# Interactive Physics Quiz

This project creates a simple, interactive multiple-choice quiz focused on basic physics concepts. It's designed as a self-contained HTML file, perfect for quick deployment or offline use. This enhanced version includes accessibility features and tracks user attempts locally.

## Features

-   **5 Multiple Choice Questions:** Covers fundamental physics topics like gravity, speed, energy, force, and Newton's laws.
-   **4 Options per Question:** Each question provides four distinct answer choices.
-   **Instant Visual Feedback:**
    -   Green background for the correct answer.
    -   Red background for an incorrect selected answer.
    -   The correct answer is always highlighted in green after a selection, even if the user chose incorrectly.
-   **Score Tracking:** Automatically calculates and displays the user's final score at the end of the quiz.
-   **Live ARIA Alerts:** Provides real-time announcements to screen readers about question changes, correct/incorrect answers, and quiz completion, enhancing accessibility.
-   **Total Attempts Tracking:** Stores and displays the total number of times the quiz has been attempted by the user in `localStorage`.
-   **Modern & Responsive Design:** Clean UI/UX built with a mobile-first approach, ensuring a professional look and feel across various devices (desktops, tablets, and smartphones).
-   **Self-Contained:** All HTML, CSS, and JavaScript are embedded within a single file, requiring no external dependencies or internet connection to run.
-   **Restart Functionality:** Users can restart the quiz to try again after completion.

## How to Use

1.  **Save the Code:** Copy the entire code block and save it as an HTML file (e.g., `physics_quiz.html`).
2.  **Open in Browser:** Double-click the saved `physics_quiz.html` file, or drag-and-drop it into any modern web browser (Chrome, Firefox, Edge, Safari, etc.).
3.  **Start Quiz:** The first question will be displayed automatically.
4.  **Answer Questions:** Select one of the four options for each question.
5.  **Get Feedback:** Immediately after selecting an answer, you'll see visual feedback (green/red), and the "Next Question" button will become active. Screen readers will also announce the result.
6.  **Navigate:** Click "Next Question" to proceed to the next question.
7.  **View Score & Attempts:** After answering all 5 questions, your final score will be displayed, and the total quiz attempts count will be updated and shown.
8.  **Restart:** Click the "Restart Quiz" button to play again. Your attempts will continue to be tracked across sessions.

## Technologies Used

*   **HTML5:** For the semantic structure and content of the quiz.
*   **CSS3:** For styling, layout, visual feedback, and ensuring a fully responsive design.
*   **JavaScript (ES6+):** For the interactive quiz logic, including question display, answer checking, score calculation, dynamic UI updates, `localStorage` management, and ARIA live region announcements.