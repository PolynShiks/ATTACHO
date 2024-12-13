# Responsive FAQ Section

This project demonstrates a responsive FAQ (Frequently Asked Questions) section built using HTML, CSS, and JavaScript. The FAQ section allows users to click on questions to reveal the corresponding answers. Only one answer can be visible at a time.

## Features
- **Responsive Design**: The layout adapts seamlessly to different screen sizes.
- **Interactive Behavior**: Users can toggle questions to reveal or hide answers.
- **Single Active Answer**: Only one answer is displayed at a time for a clean and user-friendly experience.

## File Structure
```
project-directory/
├── index.html      # Main HTML file
├── styles.css      # External CSS file for styling
├── README.md       # Documentation file
```

## How to Use
1. **Clone the repository** or copy the code files into your project directory.
2. Open `index.html` in any modern web browser to view the FAQ section.
3. The questions can be clicked to display their answers. Clicking a different question will hide the currently displayed answer and show the selected one.

## Customization
### Adding Questions and Answers
1. Open `index.html`.
2. Add a new FAQ item by duplicating the following block inside the `.faq-container` div:
   ```html
   <div class="faq-item">
       <div class="faq-question">Your Question Here?</div>
       <div class="faq-answer">Your Answer Here.</div>
   </div>
