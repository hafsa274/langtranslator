# 🌍 Language Translation Tool

## Overview
This project is a **Language Translation Tool** built in **Python** using the `googletrans` library. It allows users to translate text into multiple languages, dynamically switch target languages, and handle multiple sentences.

## 🚀 Features
- **Automatic Language Detection**  
- **Supports 10 Popular Languages**  
- **Real-time Translation of Multiple Sentences**  
- **Option to Change Target Language Anytime**  
- **Handles Invalid Inputs Gracefully**  

## 🔧 Installation
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/your-username/Language-Translator.git
   cd Language-Translator
   ```
2. **Install Dependencies**  
   ```sh
   pip install googletrans==4.0.0-rc1
   ```
3. **Run the Script**  
   ```sh
   python translator.py
   ```

## 📌 Usage
1. Select a **target language** from the available options.  
2. Enter the text you want to translate.  
3. Type `"change"` to switch the target language.  
4. Type `"exit"` to quit.

## 💡 Example Output
```
========================================
         LANGUAGE TRANSLATION TOOL        
========================================

Supported Languages:
----------------------------------------
| Code   | Language                     |
----------------------------------------
| en     | English                      |
| fr     | French                       |
| ur     | Urdu                         |
| hi     | Hindi                        |
| de     | German                       |
| es     | Spanish                      |
| zh-cn  | Chinese                      |
| ar     | Arabic                        |
| ru     | Russian                      |
| ja     | Japanese                      |
----------------------------------------

Enter the target language code (en, fr, ur, hi, de, es, zh-cn, ar, ru, ja): fr

You: Hello, how are you?
Translated (English → French): Bonjour, comment allez-vous?

You: change
Enter the target language code (en, fr, ur, hi, de, es, zh-cn, ar, ru, ja): ur

You: Nice to meet you.
Translated (English → Urdu): آپ سے مل کر خوشی ہوئی۔

You: exit
========================================
  Exiting the Language Translator.  
========================================
```

## 🌐 Supported Languages
| Code  | Language  |
|--------|------------|
| en    | English  |
| fr    | French  |
| ur    | Urdu  |
| hi    | Hindi  |
| de    | German  |
| es    | Spanish  |
| zh-cn | Chinese  |
| ar    | Arabic  |
| ru    | Russian  |
| ja    | Japanese  |

## 📄 License
This project is **open-source** and free to use under the MIT License.

## 🤝 Contributing
Feel free to contribute by improving the project or adding more features!
