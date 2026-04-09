# 🔐 Password Strength Analyzer

An advanced password security analysis tool that evaluates password strength in real-time using entropy, pattern detection, and breach analysis.

---

## 🚀 Features

* ✅ Real-time password strength analysis
* 📊 Strength score (0–100)
* 🎯 Entropy calculation (Shannon entropy)
* ⏳ Crack time estimation (multiple attacker models)
* 🧠 Pattern detection:

  * Common passwords
  * Sequential patterns (abc, 123)
  * Repeated characters
* ⚠️ Breach detection using HaveIBeenPwned API
* 🔑 Secure password generator
* 👁️ Show/Hide password toggle
* 📱 Fully responsive modern UI

---

## 🧠 How It Works

### 1. Strength Scoring

Password strength is calculated based on:

* Length
* Character diversity (uppercase, lowercase, numbers, symbols)
* Uniqueness of characters
* Pattern penalties

---

### 2. Entropy Calculation

Entropy is calculated using:

Entropy = log₂(character pool size) × password length

Higher entropy → stronger password

---

### 3. Crack Time Estimation

The system estimates brute-force attack time based on:

| Attacker Type | Speed           |
| ------------- | --------------- |
| Basic         | 10K guesses/sec |
| GPU           | 10B guesses/sec |
| Advanced      | 1T guesses/sec  |

---

### 4. Breach Detection

Uses HaveIBeenPwned API with k-anonymity:

* Password is hashed (SHA-1)
* Only first 5 characters sent to API
* Ensures privacy and security

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (Modern UI)
* JavaScript (ES6+)
* Web Crypto API

---

## 📸 Screenshot

(Add screenshot here after deployment)

---

## ▶️ How to Run

1. Clone the repo:

```
git clone https://github.com/YOUR_USERNAME/password-strength-analyzer.git
```

2. Open:

```
index.html
```

---

## 🌐 Live Demo

(Add GitHub Pages link here)

---

## 🔐 Security Note

* Passwords are never stored
* All analysis happens locally in browser
* Breach check uses privacy-safe k-anonymity model

---

## 🚀 Future Improvements

* Dark/Light theme toggle
* React version
* Backend logging (without storing passwords)
* AI-based password suggestions

---

## 👨‍💻 Author

Sivakavi B

---

