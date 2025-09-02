
# 📘 Correcto-Bot

Correcto-Bot is a **Telegram bot** designed to help users improve their English through grammar correction, practice questions, and personalized study resources.  
It combines the **Hugging Face Transformers library** with the **Telegram Bot API** to provide an interactive and user friendly learning experience.

---

## 🚀 Features
- ✅ **Grammar Fixing** – Send a sentence and get grammar-corrected feedback.  
- 📝 **Practice Tests** – Take auto-generated multiple-choice tests (vocabulary & grammar).  
- 📚 **Study Resources** – Receive tailored resources and tips to strengthen your English skills.  
- 🤝 **Interactive UI** – Powered by Telegram inline buttons for easy navigation.  

---

## 🛠️ Tech Stack
- **Python 3**
- **Hugging Face Transformers**
- **Telebot (Python Telegram Bot API)**
- **JSON** (for handling metadata and state)

---

## ⚙️ Setup & Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/YousefAdel777/correcto-bot.git
   cd correcto-bot
   
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Add your credentials:

   * Get a **Telegram Bot Token** from [BotFather](https://core.telegram.org/bots#botfather).
   * Get a **Hugging Face Token** from [Hugging Face](https://huggingface.co/settings/tokens).
   * Replace them in the code where indicated (`bot_token` and `login(token)`).

4. Run the bot:

   ```bash
   python bot.py
   ```

---

## ▶️ Usage

* Start the bot on Telegram using `/start`.
* Choose an option:

  * **Fix Grammar** → Correct a sentence.
  * **Test Your English** → Answer generated multiple-choice questions.
  * **Resources** → Get recommendations for practice.

---

## 📂 Project Structure

```
correcto-bot/
│── bot.py              # Main Telegram bot logic
│── requirements.txt    # Dependencies
│── README.md           # Documentation
```
