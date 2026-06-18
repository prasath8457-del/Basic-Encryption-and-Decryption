# 🔐 Basic Encryption & Decryption Tool

A web-based Encryption & Decryption application developed using **Python Flask**. This project demonstrates the fundamental concepts of cryptography by implementing the **Caesar Cipher Algorithm** to encrypt and decrypt user messages through an interactive browser interface.

## 📌 Project Overview

The Basic Encryption & Decryption Tool allows users to enter text and a shift value, encrypt the text using the Caesar Cipher technique, and decrypt it back to its original form. The application runs locally in a web browser and features a modern user interface with animations and visual effects.

This project is designed to help understand basic encryption concepts, data security principles, and web application development using Python.

## 🚀 Features

* Encrypt user text using Caesar Cipher
* Decrypt encrypted text back to original text
* User-friendly web interface
* Browser-based application
* Automatic browser launch on execution
* Modern animated UI
* Responsive design
* Real-time encryption and decryption results

## 🛠️ Technologies Used

* Python
* Flask
* HTML
* CSS
* JavaScript (optional enhancements)

## 📂 Project Structure

```text
Encryption-Decryption-Project/
│
├── encryption_project.py
├── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Encryption-Decryption-Project.git
```

### Navigate to the Project Folder

```bash
cd Encryption-Decryption-Project
```

### Install Dependencies

```bash
pip install flask
```

### Run the Application

```bash
python encryption_project.py
```

The application will automatically open in your default browser.

## 🔑 How It Works

### Encryption

Each alphabet character is shifted forward by a user-defined number of positions.

Example:

```text
Original Text : HELLO
Shift Value   : 3
Encrypted     : KHOOR
```

### Decryption

The encrypted text is shifted backward using the same key to retrieve the original message.

```text
Encrypted     : KHOOR
Shift Value   : 3
Decrypted     : HELLO
```

## 🎯 Learning Outcomes

* Understanding basic cryptography concepts
* Implementing Caesar Cipher encryption
* Developing web applications with Flask
* Working with HTML and CSS for UI design
* Understanding data protection fundamentals

## 📸 Project Demo

```text
Input:
Hello World
Shift Value: 3

Output:
Encrypted Text: Khoor Zruog
Decrypted Text: Hello World
```

## 💡 Future Enhancements

* Multiple encryption algorithms
* AES and RSA implementation
* File encryption support
* Dark and light mode
* Encryption history
* Copy-to-clipboard functionality
* Download encrypted results

## 👨‍💻 Author

Prasath M

## 📜 License

This project is developed for educational and learning purposes.
