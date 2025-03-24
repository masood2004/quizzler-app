# Quizzler App 🧠

![Quizzler App Screenshot](https://github.com/masood2004/quizzler-app/blob/main/images/screenshot.png?raw=true)

## 🌟 Overview

**Quizzler** is a sleek and interactive quiz application built with **Python** and **Tkinter**. It dynamically fetches trivia questions from the [Open Trivia Database](https://opentdb.com/) and presents them in a **True/False** format. With real-time feedback and score tracking, Quizzler offers a seamless and engaging quiz experience. 🎯

---

## 🚀 Features

- **🌐 Dynamic Question Fetching**: Pulls fresh trivia questions from the OpenTDB API.
- **✅ True/False Interface**: Simple button-based interaction for quick answers.
- **📊 Score Tracking**: Real-time score updates displayed prominently.
- **🎨 Visual Feedback**: Instant color-coded responses (🟢 Correct / 🔴 Incorrect).
- **📱 Responsive Design**: Clean, modern UI with a mobile-friendly layout.

---

## 🛠️ Installation

1. **📥 Clone the Repository**:
   ```bash
   git clone https://github.com/masood2004/quizzler-app.git
   cd quizzler-app
   ```

2. **🔧 Install Dependencies**:
   ```bash
   pip install requests  # Required for API interactions
   ```

3. **▶️ Run the App**:
   ```bash
   python main.py
   ```

---

## 📂 Project Structure

| File               | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `data.py`          | Fetches questions from the OpenTDB API. 🌐                                  |
| `question_model.py`| Defines the `Question` class model. 📝                                      |
| `quiz_brain.py`    | Manages quiz logic, scoring, and progression. 🧠                            |
| `ui.py`            | Handles the GUI using Tkinter. 🖥️                                          |
| `main.py`          | Entry point to initialize the quiz and UI. 🚀                               |

---

## 🎮 Usage

1. **Start the Quiz**: Launch the app, and questions will load automatically.
2. **Answer**: Click the **✅ True** or **❌ False** button to respond.
3. **Feedback**: Immediate color change (🟢/🔴) indicates correctness.
4. **Completion**: After 10 questions, view your final score. 🏆

---

## 🤝 Contributing

Contributions are welcome!  
🔹 **Report Bugs**: Open an [Issue](https://github.com/masood2004/quizzler-app/issues).  
🔹 **Suggest Features**: Submit a **Pull Request** with detailed descriptions.  

---

## 📜 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgments

- **Open Trivia Database** for providing free trivia questions. 🌐
- **Tkinter** for enabling cross-platform GUI development. 🖥️

---

Test your knowledge and challenge yourself with **Quizzler**! 🎉  
*Let the trivia begin!* 🧠✨
