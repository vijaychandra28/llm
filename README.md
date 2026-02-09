# 🧠 AI Debate Partner – Enhanced Version

An interactive **AI-powered philosophical debate application** built with **Streamlit**. The app challenges users by always taking the *opposing stance*, helping sharpen critical thinking, logic, and argumentation skills.

---

## 🎯 Overview

AI Debate Partner enables intelligent, structured debates on philosophical and abstract topics. Users choose a topic, set debate difficulty and response style, and argue their position—while the AI responds with a well-reasoned counter‑argument.

This enhanced version focuses on:

* Professional UI/UX
* Advanced prompt engineering
* Customizable debate experience
* Hackathon‑ready polish

---

## ✨ Key Improvements

### 1. Enhanced UI / UX

* Gradient header with branding
* Color‑coded chat (User vs AI)
* Sidebar‑based configuration panel
* Responsive layout
* Custom CSS styling
* Smooth transitions & visual clarity

### 2. Advanced Features

#### 🔧 Configurable Settings

* **Debate Difficulty:** Beginner → Expert
* **Response Style:** Balanced, Aggressive, Socratic, Academic
* **Response Length:** 50–300 words (slider)

#### 🧠 Smart Debate Management

* Conversation history
* Argument count tracking
* Download debate transcript (.txt)
* Quick starter prompts
* Preset + custom topics

### 3. Better AI Prompting

* Dynamic system prompts
* Style‑specific instructions
* Difficulty‑aware reasoning
* Structured responses
* Prevents repetition

### 4. User Experience Enhancements

* Loading spinner during AI thinking
* Friendly error messages
* Clear message separation
* One‑click reset for new debates

---

## 📋 Features Comparison

| Feature           | Original | Enhanced           |
| ----------------- | -------- | ------------------ |
| Topics            | 3 preset | 8 preset + custom  |
| Difficulty Levels | Basic    | 4 adaptive levels  |
| Response Styles   | None     | 4 styles           |
| UI Design         | Basic    | Professional + CSS |
| Statistics        | ❌        | ✅                  |
| Export Debate     | ❌        | ✅ (.txt)           |
| Quick Prompts     | ❌        | ✅                  |
| Settings Panel    | ❌        | ✅ Sidebar          |

---

## 🚀 Installation & Setup

### Prerequisites

```bash
pip install streamlit openai python-dotenv
```

### Environment Setup

Set your OpenAI API key:

```bash
export OPENAI_API_KEY="your-api-key-here"
```

Or create a `.env` file:

```bash
echo "OPENAI_API_KEY=your-api-key-here" > .env
```

### Run the Application

```bash
streamlit run ai_debate_partner.py
```

---

## 📖 How to Use

### 1️⃣ Choose a Topic

* Select from preset philosophical topics
* Or enter a custom topic

### 2️⃣ Configure Settings (Sidebar)

#### Debate Difficulty

* **Beginner:** Simple language, basic ideas
* **Intermediate:** Logical reasoning + examples
* **Advanced:** Philosophical references
* **Expert:** Deep analysis & complex logic

#### Response Style

* **Balanced:** Respectful, multi‑angle
* **Aggressive:** Assertive, challenging
* **Socratic:** Question‑driven
* **Academic:** Formal & scholarly

#### Response Length

* Adjust verbosity (50–300 words)

### 3️⃣ Enter Your Argument

* Write your stance
* Use quick prompts if needed
* Submit to receive AI counter‑argument

### 4️⃣ Continue the Debate

* Read AI response
* Rebut and refine your reasoning

### 5️⃣ Export & Review

* Download debate transcript
* Review statistics
* Start fresh anytime

---

## 🎨 UI Components

### Header

* Gradient title
* Subtitle & branding

### Sidebar (Settings)

* Difficulty selector
* Style selector
* Response length slider
* Statistics
* Clear debate button

### Main Area

* Topic selection
* Message history
* Argument input
* Quick prompts
* Submit button

### Footer

* Usage tips
* Debate philosophy reminder

---

## 🧠 How It Works

### System Prompt Logic

* Injects topic, difficulty & style
* Forces opposing stance
* Controls structure & tone

### Difficulty Adaptation

* Beginner → Simple concepts
* Intermediate → Examples & logic
* Advanced → Philosophical nuance
* Expert → Deep reasoning & citations

### Memory Management

* Full debate history stored in session
* Context preserved across turns
* Repetition avoidance

---

## 📊 Code Architecture

```
ai_debate_partner.py
│
├── Configuration
│   ├── OpenAI setup
│   ├── Page config
│   └── Custom CSS
│
├── UI Components
│   ├── Header
│   ├── Sidebar
│   ├── Topic selector
│   └── Footer
│
├── State Management
│   ├── Session memory
│   ├── Statistics
│   └── Debate tracking
│
├── Core Functions
│   ├── get_depth_instruction()
│   ├── get_style_instruction()
│   └── AI response generator
│
└── Features
    ├── Chat display
    ├── Export debate
    ├── Quick prompts
    └── Error handling
```

---

## 🎯 Best Practices

* Start with a clear stance
* Use examples
* Try different styles
* Increase difficulty gradually
* Export debates for review

---

## 🔧 Customization

### Add New Topics

```python
topics.append("Your New Topic")
```

### Add New Response Style

```python
style_map["Your Style"] = "Custom instruction"
```

### Change AI Model

```python
model="gpt-4"  # or gpt-4-turbo
```

---

## 🐛 Troubleshooting

**API Key Error**
→ Ensure `OPENAI_API_KEY` is set

**Rate Limit**
→ Wait or upgrade OpenAI plan

**Long Memory Issues**
→ Clear debate history

---

## 📈 Future Enhancements

* Multi‑AI debates
* Argument scoring
* AI judge
* Fact‑checking
* Voice input
* Collaborative debates
* Citation linking

---

## 📄 License

This project is intended for **educational and hackathon use**. Please ensure compliance with OpenAI usage policies.

---

## 🙏 Credits

Built to enhance the original AI Debate Partner concept with:

* Professional UI/UX
* Advanced AI prompting
* Configurable debate logic
* Hackathon‑ready design

Happy debating 🚀
