# budget-chatbot

# 💸 Budget Bot

A smart budgeting assistant powered by **LangChain** and **Chainlit**.

## 🚀 Quick Start

Follow these steps to set up and run the project locally.

### 🔧 Prerequisites

- Python 3.8+
- Git

### 📥 Clone the Repository

```bash
git clone <repo-url>
cd budget-bot

python -m venv venv
# Activate the environment
source venv/bin/activate       # On macOS/Linux
venv\Scripts\activate          # On Windows


pip install langchain chainlit
pip install -U langchain-community
pip install -r requirements.txt

#### Read to run
chainlit run app.py -w
