# 🍽️ Restro-Cuisine Generator

### GenAI-Powered Restaurant & Cuisine Idea Generator

Restro-Cuisine Generator is a Generative AI-powered web application that helps aspiring food entrepreneurs explore creative restaurant concepts. It generates fancy restaurant names, cuisine ideas, menu suggestions, recipes, and estimated calories per serving based on user-selected preferences.

The application leverages **LangChain** and **Google Gemini API** to generate creative, context-aware suggestions through an interactive **Streamlit** interface.

## ✨ Features

- **Restaurant Name Generation:** Generates unique and creative restaurant names.
- **Cuisine Suggestions:** Recommends cuisine concepts based on restaurant themes and preferences.
- **Menu Generation:** Suggests interesting and diverse food items.
- **Recipe Generation:** Provides recipes for suggested dishes.
- **Calorie Estimation:** Displays estimated calories per serving.
- **Interactive UI:** Offers a simple and user-friendly interface for real-time input and AI-generated results.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Generative AI:** Google Gemini API
- **LLM Framework:** LangChain
- **Frontend:** Streamlit

## ⚙️ How It Works

1. Users select their preferred cuisine type and food preferences.
2. The application processes the inputs using LangChain prompt templates and chains.
3. Google Gemini API generates context-aware restaurant and cuisine suggestions.
4. Results are displayed dynamically through the Streamlit interface.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Pratiksha248/GenAI-Restro-Cuisine-Generator.git
cd GenAI-Restro-Cuisine-Generator
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure API Key

Create a `.env` file in the project directory and add your Google Gemini API key:

```env
GOOGLE_API_KEY=your_gemini_api_key
```

### 4. Run the Application

```bash
streamlit run app.py
```

## 🎯 Project Objective

To explore the practical implementation of Generative AI using LangChain and Google Gemini API while building an interactive application that simplifies restaurant ideation and menu planning for aspiring food entrepreneurs.
