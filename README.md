# 🧩 compquiz

![Status](https://img.shields.io/badge/status-live-success?style=flat&color=brightgreen) 
![Made with](https://img.shields.io/badge/made%20with-HTML%2C%20CSS%2C%20JS-orange)

**compquiz** is a web-based **Quiz Game** that allows users to select a range of questions and play with multiple-choice answers.  
Provides instant feedback, highlights correct/incorrect options, and shows the final score.

🔗 **Live Demo:** [compquiz.netlify.app](https://compquiz.netlify.app/)

---

## ✨ Features

- 📌 Select starting and ending question numbers  
- 🎯 Choose the number of questions to attempt  
- 🖊️ Multiple-choice questions with randomized options  
- ✅ Immediate feedback for correct or incorrect answers  
- 📊 Displays final score at the end of the quiz  
- 📱 Fully responsive design  
- 🔄 Option to restart the quiz after completion  

---

## 🚀 How to Use

1. Open `index.html` in a web browser  
2. Enter **starting** and **ending** question numbers, and number of questions  
3. Click **Sınağa Başla** to start the quiz  
4. Select an answer and click **Cavabla**  
5. Click **Növbəti** to move to the next question  
6. At the end, your score will be displayed and you can restart the quiz  

---
## 📂 File Structure
/compquiz

│── .vscode/ # VSCode settings (optional)

│── README.md # This file

│── comp.txt # Quiz questions and answers

│── index.html # Main HTML file

---

## 🛠️ Technologies Used

- **HTML5**  
- **CSS3** (Flexbox, Transitions, Responsive Design)  
- **JavaScript (ES6)** → DOM Manipulation, Event Handling, Fetch API  

---

## ⚡ Notes

- Questions are loaded from a `comp.txt` file.  
- Correct answers in the file should start with `√` and incorrect ones with `•`.  
- Quiz shuffles questions and answers dynamically for each playthrough.  
- Ensure the `meta viewport` tag is included for mobile responsiveness:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">



