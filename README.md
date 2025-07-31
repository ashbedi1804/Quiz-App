# Quiz‑App

A simple web-based quiz application built with **HTML**, **CSS**, and **Vanilla JavaScript**. Users upload a CSV file of questions, then answer multiple-choice quizzes and see their results.

---

## 📂 Project Structure

```
Quiz‑App/
├── index.html        # Home page with CSV upload form
├── script.js         # JS logic for uploading and parsing CSV
├── style.css         # Styles for index.html
├── Questions.html    # Displays questions and options
├── script1.js        # Handles quiz rendering and navigation
├── quizstyle.css     # Stylesheet for Questions.html
├── result.html       # Shows quiz results (correct/wrong counts)
├── images/           # UI assets (e.g. buttons, background)
└── README.md         # Documentation (this file)
```

---

## 🚀 Features

- Support for any number of questions and options in CSV format.
- CSV must follow strict formatting:  
  `question,option1,option2,...,option‑n,correct‑option`
- Displays multiple‑choice questions with radio buttons.
- Tracks user selections and displays a result summary.

---

## ⚙️ How to Use

1. **Clone the repo**
   ```bash
   git clone https://github.com/ashbedi1804/Quiz-App.git
   cd Quiz-App
   ```

2. **Create a CSV file** in the following format:
   ```
   What is the capital of France?,Paris,London,Berlin,Rome,Paris
   What is 2+2?,3,4,5,6,4
   ```

3. **Open** `index.html` in your browser to:
   - Upload the CSV file.
   - Navigate through the quiz.
   - View result summary on the `result.html` page.

---

## 🧩 How It Works

- **index.html**: Uploads CSV and passes data to next pages.
- **Questions.html + script1.js**: Parses the CSV and dynamically renders questions/options.
- **result.html**: Compares answers and displays count of correct vs. wrong responses.

---

## 🔧 Customization & Development

- Modify styling in `style.css` and `quizstyle.css`.
- Enhance logic in `script.js` or `script1.js`:
  - Add timers
  - Navigation controls
  - Keyboard support
- Extend quiz features:
  - Progress tracking
  - Scoring system
  - Feedback for each question

---

## 🧪 Manual Testing

- Upload a valid CSV and navigate through each question.
- Test edge cases:
  - Empty fields
  - Incorrect answer format
  - Duplicate questions or options
- Verify result accuracy

---

## 📝 Contribution & Attribution

- Contributions welcome! Fork the repo and create a pull request.
- Raise issues for bugs, feature requests, or suggestions.

---

## 📞 Contact

- GitHub: [@ashbedi1804](https://github.com/ashbedi1804)

Thanks for using or improving Quiz‑App! 🎓
