# 💻 Code Explainer

A Flask-based web application that helps beginners understand programming code by breaking it into individual tokens, explaining each token, checking syntax, highlighting code, and executing programs in multiple programming languages.

## 🚀 Features

- 🔍 Token-wise code explanation
- 📝 Syntax checking (Python)
- 🎨 Syntax highlighting
- ▶️ Execute code directly from the browser
- 🌐 Supports multiple programming languages:
  - Python
  - C
  - C++
  - Java
- 📚 Beginner-friendly interface

## 🛠️ Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- Pygments
- Regular Expressions (Regex)
- AST (Python Syntax Checking)

## 📂 Project Structure

```
code-explainer/
│── app.py
│── token_explainer.py
│── TempCode.java
│── temp_code.c
│── temp_code.cpp
│── templates/
│   ├── index.html
│   ├── result.html
│   ├── syntax.html
│   └── error.html
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/code-explainer.git
```

### 2. Go to the project directory

```bash
cd code-explainer
```

### 3. Install dependencies

```bash
pip install flask pygments
```

### 4. Run the application

```bash
python app.py
```

The application will start on:

```
http://127.0.0.1:5000/
```

## 📖 How It Works

1. Select a programming language.
2. Paste or write your code.
3. Click **Analyze**.
4. The application:
   - Breaks the code into tokens.
   - Explains each token.
   - Checks syntax (Python).
   - Highlights the source code.
   - Executes the program and displays the output.

## 📸 Screenshots

Add screenshots of your application here.

Example:

```
screenshots/
├── home.png
├── result.png
└── syntax.png
```

## 🔮 Future Improvements

- Support more programming languages.
- AI-powered code explanation.
- Better syntax checking for C, C++, and Java.
- User authentication.
- Save explanation history.
- Dark mode.

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/your-username

## 📄 License

This project is for educational purposes.
