# 🕵️‍♂️ Secret Code Language
Welcome to the Secret Code Language project! This Python program allows you to encode and decode messages using a fun and secretive coding technique, making your communications more playful and secure.
![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🚀 Features
-Encoding: Transform readable messages into jumbled code.
-Decoding: Retrieve the original message from the coded format.
-Word Handling: Custom rules for short and long words.

## 📖 Table of Contents

- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage Example](#usage-example)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🔍 How It Works
### Encoding Process
- For words with 3 or more characters:
- The first letter is moved to the end.
- Three random characters are added at the beginning and end.
- For words with fewer than 3 characters, the word is simply reversed.

### Decoding Process
- For words with fewer than 3 characters, they are reversed back.
- For longer words, the 3 random characters are stripped from the start and end, reconstructing the original word.

## ⚙️ Getting Started

### Prerequisites
- Python 3.x

### Installation
1. Clone this repository:
      ```bash
   git clone https://github.com/yourusername/secret-code-language.git
       ```

3. Navigate to the project directory:
    ```bash
   cd secret-code-language
    ```

5. Running the program:
   Run the program using Python:
    ```bash
   python secret_code_language.py
    ```

####  💬Usage Example
#### Encoding 
     Input: "Hello World"
Output: "xyzxollHeabc123"

#### Decoding 
     Input: "xyzxollHeabc123"
Output: "Hello"

##### Contributing🤝
Contributions are welcome! If you have suggestions for new features or improvements, please fork the repository and submit a pull request. For bug reports or feature requests, open an issue.

###### 📄 License
This project is licensed under the MIT License.

###### 📬 Contact
For questions or feedback, feel free to reach out to:
snehasinghania005@gmail.com








    



