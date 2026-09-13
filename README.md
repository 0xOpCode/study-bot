<div align="center">

  # 📚 StudyBot AI
  ### Intelligent Telegram Mentor & Syllabus-Aligned Exam Preparation Bot

  [![Python](https://img.shields.io/badge/Python-3.9+-3776AB.svg?style=flat-square&logo=python&logoColor=white)](https://python.org)
  [![Telegram Bot API](https://img.shields.io/badge/Telegram-Bot%20API-26A5E4.svg?style=flat-square&logo=telegram&logoColor=white)](https://core.telegram.org/bots/api)
  [![AI Core](https://img.shields.io/badge/AI%20Engine-LLM%20Grounded-4285F4.svg?style=flat-square)](https://ai.google.dev/)
  [![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
  [![Maintained](https://img.shields.io/badge/Maintained%20by-0xOpCode-orange.svg?style=flat-square)](https://github.com/0xOpCode)

  <p align="center">
    <b>An interactive AI-powered Telegram educational mentor designed for structured concept explanation, doubt clearing, and automated MCQ quiz generation aligned with academic syllabi.</b>
  </p>

  <p align="center">
    <a href="#-key-features">Features</a> •
    <a href="#-command-reference">Commands</a> •
    <a href="#-syllabus-coverage">Syllabus</a> •
    <a href="#-setup--deployment">Setup</a> •
    <a href="#-maintainer">Maintainer</a>
  </p>

</div>

---

## ⚡ Key Features

- **🎯 Syllabus-Constrained Explanations:** Tailored system prompts keep responses strictly focused on core academic curricula (Science, Mathematics, Social Studies), eliminating out-of-scope hallucinations.
- **📝 Automated MCQ Generator:** Generates structured multiple-choice questions on demand for active recall and self-assessment.
- **💡 Structured Point-Wise Output:** Answers are formatted with rich HTML markup (`<b>`, `<i>`, bullet points) for enhanced mobile readability.
- **👥 Group & Direct Chat Support:** Operates seamlessly in private student chats or shared student study groups with user access controls.
- **☁️ Cloud Deployable:** Includes production `Procfile` ready for Heroku, Railway, or VPS background daemon execution.

---

## 🤖 Command Reference

| Command | Arguments | Description |
| :--- | :--- | :--- |
| `/start` | — | Initializes the bot and presents the curriculum menu. |
| `/answer` | `<topic or query>` | Requests a clear, structured explanation for a specific subject doubt. |
| `/mcq` | `<topic>` | Generates a multiple-choice practice question with answer choices. |
| `/info` | — | Displays Telegram user ID, chat telemetry, and session state. |

---

## 📖 Syllabus Coverage

The bot comes pre-configured with contextual knowledge across core secondary school curricula:

- **🔬 Science:** Chemical Reactions, Acids/Bases/Salts, Metals, Carbon Compounds, Life Processes, Heredity & Evolution, Optics, Electricity & Magnetism.
- **📐 Mathematics:** Real Numbers, Polynomials, Linear & Quadratic Equations, Coordinate Geometry, Trigonometry, Statistics & Probability.
- **🌍 Social Sciences:** Nationalism in Europe/India, Resources, Agriculture, Federalism, Economic Development.

---

## 🚀 Setup & Deployment

### Prerequisites
- Python 3.9+
- A valid Telegram Bot Token from [@BotFather](https://t.me/BotFather)

### Installation

```bash
# Clone the repository
git clone https://github.com/0xOpCode/study-bot.git
cd study-bot

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Environment Configuration

Set the required environment variable:

```bash
export BOT_TOK="your_telegram_bot_token"
```

### Running Locally

```bash
python main.py
```

### Cloud Deployment (Heroku / Railway)
The project includes a `Procfile`:
```text
worker: python main.py
```

---

## 👨‍💻 Maintainer

Created and maintained by **[0xOpCode](https://github.com/0xOpCode)**.
