# 🎥 AI-Powerd-Audience-Intelligence-System

### Prompt-Driven YouTube Insight Engine (Powered by LLMs)

## 📌 Overview

TubePulse-Analytics is a flexible, AI-powered system that extracts YouTube comments and generates **custom insights using Large Language Models (Groq API)**.

Unlike traditional sentiment analysis tools, this project is **prompt-driven**, meaning the type of insights generated can be completely customized by simply modifying the input prompt.

👉 This transforms the system from a fixed pipeline into a **dynamic insight generation engine**.

---

## ⚙️ What Makes This Unique

💡 **Insights are not hardcoded — they are generated dynamically**

* Want sentiment? → Change prompt
* Want audience pain points? → Change prompt
* Want content suggestions? → Change prompt
* Want business insights? → Change prompt

🔁 The same data → **infinite types of insights**

---

## 🧠 Core Idea

This project demonstrates how:

> **Data + Prompt Engineering + LLM = Unlimited Insight Generation**

Instead of building multiple analytics tools, a single system can generate different perspectives just by modifying prompts.

---

## 🔥 Key Features

* 🎥 **YouTube Comment Extraction**

  * Fetches real-time comments using API

* 🧹 **Text Preprocessing**

  * Cleans and prepares raw text

* 🤖 **LLM-Powered Insight Generation (Groq API)**

  * Generates human-like insights
  * Fully customizable via prompts

* 🔄 **Dynamic Prompt System**

  * Change prompt → Change output
  * No need to modify core logic

* 📊 **Structured Outputs**

  * Insights ready for analysis or visualization

---

## 🧩 How It Works

1. Extract comments from YouTube
2. Clean and preprocess text
3. Send data to Groq API with a prompt
4. Generate insights based on prompt intent

---

## 🧪 Example Prompts

You can modify prompts like:

```python
prompt = "Analyze audience sentiment"
```

or

```python
prompt = "Identify major complaints and user pain points"
```

or

```python
prompt = "Suggest how the creator can improve engagement"
```

or even:

```python
prompt = "Summarize audience psychology and emotional response"
```

👉 Same data, completely different insights.

---

## 🚀 How to Run

### Step 1: Setup

* Add your YouTube API key
* Add your Groq API key

---

### Step 2: Modify Prompt

Inside the notebook:

```python
prompt = "Your custom insight instruction"
```

---

### Step 3: Run Notebook

* Comments will be fetched
* Insights will be generated dynamically

---

## 📈 Use Cases

* 📢 Content Strategy Optimization
* 📊 Audience Behavior Analysis
* 🛍️ Product Feedback Mining
* 📣 Marketing Insights
* 🧠 Psychological Analysis of Audience

---

## 🧩 Tech Stack

* Python
* YouTube Data API
* Groq API (LLM Inference)
* NLTK / Pandas

---

## ✨ Future Improvements

* Real-time dashboard
* Multi-video comparison
* Prompt templates library
* Integration with social platforms

---

## 👨‍💻 Author

Built as a next-generation NLP system demonstrating the power of **prompt engineering + LLM-driven analytics**.

---

## ⭐ If you found this useful

Give it a star ⭐ and explore the power of prompt-driven insights!
