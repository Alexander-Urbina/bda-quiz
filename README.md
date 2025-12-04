# Bayesian Data Analysis Quiz App

A standalone, interactive quiz application for practicing Bayesian Data Analysis concepts from quizzes 1-9.

## Features

- **Multiple Quiz Modes:**
  - **Explore**: Browse all quizzes and sections
  - **Random Section**: Practice a random section from any quiz
  - **Random Question**: Practice a random question from all quizzes
  - **Progress**: Track your progress across all quizzes

- **Section Descriptions**: Contextual information displayed for each section to help understand the topic before answering questions

- **Progress Tracking**: 
  - Track correct and wrong answers
  - View progress by quiz and by section
  - Accuracy percentages
  - Reset functionality for retaking quizzes

- **User Experience:**
  - Light and dark mode support
  - Responsive design (mobile, tablet, desktop)
  - MathJax support for mathematical formulas
  - Clean, modern UI

## Usage

Simply open `index.html` in your web browser, or visit the GitHub Pages site once deployed.

## Structure

- `index.html` - Main application file (standalone HTML with embedded CSS and JavaScript)
- `quiz_data.js` - Quiz data containing all questions, options, correct answers, explanations, and section descriptions

## Development

To update quiz content:
1. Edit the R Markdown files in the source repository
2. Run `parse_quizzes.py` to regenerate `all_quizzes.json`
3. Update `quiz_data.js` with the new JSON data
4. Commit and push changes

## License

Educational use for Bayesian Data Analysis course.

