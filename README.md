# Language Translation Tool

## Overview
This project is a **Language Translation Tool** built in **Python** using the `googletrans` library. It allows users to translate text into multiple languages, dynamically switch target languages, and handle multiple sentences.

## Features
- **Automatic Language Detection**  
- **Supports English, French, Urdu, Hindi, and German**  
- **Real-time translation** of multiple sentences  
- **Option to change the target language anytime**  
- **Handles invalid inputs gracefully**  

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/Language-Translator.git
   cd Language-Translator
   ```
2. **Install dependencies**
   ```sh
   pip install googletrans==4.0.0-rc1
   ```
3. **Run the script**
   ```sh
   python translator.py
   ```

## Usage
1. Select a **target language** from the available options.  
2. Enter the text you want to translate.  
3. Type `"change"` to switch the target language.  
4. Type `"exit"` to quit.

## Example Output
```
Supported Languages:
en: English
fr: French
ur: Urdu
hi: Hindi
de: German

Enter the target language code (en, fr, ur, hi, de): fr

You: Hello, how are you?
Translated (English → French): Bonjour, comment allez-vous?

You: change
Enter the target language code (en, fr, ur, hi, de): ur

You: Nice to meet you.
Translated (English → Urdu): آپ سے مل کر خوشی ہوئی۔

You: exit
Exiting.
```

## Supported Languages
- **English (`en`)**  
- **French (`fr`)**  
- **Urdu (`ur`)**  
- **Hindi (`hi`)**  
- **German (`de`)**  

## License
This project is **open-source** and free to use.
