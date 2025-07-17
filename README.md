 Morse Code Quiz Generator

An interactive Morse Code quiz application built using **Java Swing GUI** in **BlueJ**. This tool helps users learn Morse Code through engaging quizzes that challenge them to encode and decode messages.

🧠 Features

* Graphical User Interface (GUI) built with Java Swing.
* Two quiz modes:

  * **Decode Mode** – Convert Morse code into plain English.
  * **Encode Mode** – Convert plain English into Morse code.
* Randomized questions to keep the quizzes fresh.
* Real-time feedback on answers.
* Score tracking to assess learning progress.

🖥️ Technology Stack

* Java (Core + Swing for GUI)
* Developed and tested in **BlueJ** IDE

 🚀 Getting Started

 Prerequisites

* Java Development Kit (JDK) installed (version 8 or above)
* [BlueJ IDE](https://bluej.org) installed

Running the Application

1. Clone the repository or download the ZIP:

   ```bash
   git clone https://github.com/astro-prog/Morse-Code-quiz-generator.git
   ```

2. Open the project folder in **BlueJ**.

3. Compile all classes.

4. Right-click on the main class (e.g., `MorseQuizMain` or equivalent) and select **"void main(String\[] args)"** to run the program.

### Note:

All GUI components and logic are written in Java using the Swing library, and the code is designed for simplicity and ease of understanding by beginner Java learners.

 📁 Project Structure

```
Morse-Code-quiz-generator/
├── MorseQuizMain.java        # Main GUI class
├── MorseEncoder.java         # Class for encoding text to Morse
├── MorseDecoder.java         # Class for decoding Morse to text
├── MorseQuizGenerator.java   # Logic for generating quiz questions
├── MorseDictionary.java      # Contains mappings for Morse code
└── README.md                 # Project documentation
```

 📚 Morse Code Reference

* Letters (A–Z) and digits (0–9) supported
* Example:

  * `A` → `.-`
  * `B` → `-...`
  * `5` → `.....`

✨ Contributions

Contributions are welcome! If you have suggestions for improvements or additional features (e.g., sound playback, difficulty levels), feel free to fork the repo and submit a pull request.

made with &hearts; by astro
