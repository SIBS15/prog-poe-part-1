# CyberSecurityBot – README

## 📌 Project Overview

CyberSecurityBot is a simple **C# console application** designed to educate users about basic cybersecurity concepts. The program interacts with the user through a chatbot interface, provides information on common security threats, and plays an audio greeting when the application starts.

---

## ⚙️ Features

* 🎧 Plays a greeting sound on startup
* 🤖 Interactive chatbot interface
* 🔐 Provides information on cybersecurity topics such as:

  * Trojan attacks
  * Phishing
  * Password security
  * Malware & ransomware
  * Spyware & viruses
  * Social engineering
  * Safe browsing practices
* 👤 Stores user name for personalized interaction
* 🖥️ ASCII art displayed on startup

---

## 🗂️ Project Structure

```
CyberSecurityBot/
│
├── Program.cs        # Entry point of the application
├── Chatbot.cs        # Core chatbot logic and cybersecurity topics
├── User.cs           # User model (stores user name)
├── AudioPlayer.cs    # Handles audio playback
├── greetings.wav     # Audio file for greeting
├── .csproj           # Project configuration file
```

---

## 🚀 How It Works

1. The program starts in `Program.cs`.
2. An audio greeting (`greetings.wav`) is played using `AudioPlayer`.
3. ASCII art is displayed in the console.
4. The chatbot (`Chatbot.cs`) is initialized.
5. The user interacts with the chatbot by typing input.
6. The bot responds with cybersecurity tips and explanations.

---

## 🧠 Key Components

### 1. Program.cs

* Entry point of the application
* Initializes audio and chatbot
* Displays ASCII banner

### 2. Chatbot.cs

* Contains predefined cybersecurity topics
* Handles user interaction and responses
* Uses a simple conversational flow

### 3. User.cs

* Stores user information (currently only name)
* Enables personalization

### 4. AudioPlayer.cs

* Plays `.wav` audio files
* Resolves file paths dynamically
* Handles errors if the file is missing

---

## 💻 Requirements

* .NET (Core / SDK compatible with project)
* Windows OS (for `System.Media.SoundPlayer` support)

---

## ▶️ How to Run

1. Open the project in Visual Studio or VS Code
2. Build the solution
3. Run the application:

   ```
   dotnet run
   ```
4. Follow the prompts in the console

---

## ⚠️ Notes

* Ensure `greetings.wav` is located in the correct output directory (`bin/Debug/...`)
* Audio playback may not work on non-Windows systems
* This is an educational project, not a production-grade chatbot

---

## 📚 Learning Purpose

This project demonstrates:

* Basic C# object-oriented programming
* Console input/output handling
* Working with audio in C#
* Structuring a simple chatbot
* Introduction to cybersecurity concepts

---

## ✍️ Author

Developed as part of a programming assignment (PROG POE Part 1).

---

## 📄 License

This project is for educational use only.
