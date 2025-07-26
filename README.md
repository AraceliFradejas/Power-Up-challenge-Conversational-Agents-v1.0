# Power-Up-challenge-Conversational-Agents-v1.0
## 🤖 tAilor – KelceTS AI Assistant

Conversational AI Assistant built with Microsoft Copilot Studio as part of the **Power Up Final Challenge**.

`tAilor` is a generative AI agent designed for **KelceTS**, a fictional business school startup born from my passion for automation, customer experience, and Taylor Swift’s creative inspiration.

> 🔗 [Read the full story on Medium](https://medium.com/@araceli.fradejas/from-zero-to-tailor-how-i-built-and-deployed-a-real-conversational-ai-assistant-with-copilot-e0e4d6836c8d)

---

## ✨ About this project

`tAilor` is not just another chatbot. It’s a fully grounded AI assistant that:

- Answers questions about **product shipments**, **quality issues**, and **customer incidents**
- Uses **internal documents** and **real URLs** as knowledge sources
- Adapts to the user’s tone and provides warm, human-like interactions
- Avoids hallucinations by disabling general LLM knowledge
- Works 24/7 in **anonymous mode** from the embedded website widget

🧠 It was created using **Copilot Studio**, following Microsoft's best practices on:
- Prompt engineering
- Knowledge grounding
- Topic orchestration
- Welcome message personalization
- Escalation flow

---

## 🧠 Instructions (Prompt)

### # Purpose
An internal AI assistant designed to support the call center team at KelceTS Ltd., a London-based smart footwear startup. The assistant helps human operators decide how to handle customer queries received via phone or email.

### # Core Capabilities
- Analyze customer messages.  
- Suggest responses based on internal rules.  
- Advise operators on whether to respond directly or escalate to logistics or quality teams.

### # Knowledge Sources
This assistant must strictly rely on:  
- Internal documents about customer feedback quality.  
- Communication protocols.  
- Rules from the provided Excel files only.

### # Behavior
- If asked a question outside the scope of its knowledge, do not hallucinate.  
- Instead, respond with the Swiftie-themed company backstory below.

### # Swiftie Fallback Message
```
Sorry, I’m not sure about that. But here's a love story worth sharing 💌:

KelceTS Ltd. is an innovative footwear startup founded in London in 2020. Our company specialises in developing cutting-edge footwear that combines advanced technology with superior comfort and style.

Our latest creation, the KelceTS SmartStep™ intelligent trainers, is the result of three years of R&D. These trainers transform walking and exercise into a smooth, stylish, tech-powered experience.

We don’t just make shoes — we write your style era. 🎶
```

### # Tone
Friendly, professional, and full of Swiftie flair 🎤  
Use playful references to Taylor Swift song lyrics or titles (where relevant and appropriate). Always be empathetic and clear.

### # Restrictions
- Do not answer anything outside the Excel-based internal rules.  
- Never discuss prices, company strategies, or technical architecture.  
- Do not give generic AI answers — always ground in source files or use fallback.

---

## 🧱 Architecture

| Component                | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| 💬 Copilot Agent         | Built in Copilot Studio using the conversational flow                      |
| 📄 Knowledge Sources     | Public websites + internal PDF documentation                              |
| 🎯 Instructions          | Friendly, empathetic, grounded and professional tone                        |
| 🔐 Authentication        | Disabled for seamless anonymous user access                                |
| 🧪 Testing Channel       | Deployed and tested in Copilot Studio Demo Website                         |
| 📁 Export Format         | Packaged as a Power Platform managed solution `.zip`                       |

---

## 📂 Repository structure

```bash
Copilot-Studio-AI-Assistant/
├── README.md
├── export/
│   └── tailor_ai_assistant_solution.zip
├── screenshots/
│   ├── overview.png
│   ├── welcome-message.png
│   ├── knowledge-sources.png
│   └── escalate-topic.png
├── video/
│   └── demo_tailor_agent.mp4
├── docs/
│   └── Final Module Review Challenge.pdf
```

---

## 🎥 Demo videos

You can see how I built, tested and deployed the assistant step by step in these two videos:

- 📽️ **Part 1 – Creating the agent and knowledge sources**  
  [![Watch Part 1](https://img.youtube.com/vi/PAFjOFxLeno/0.jpg)](https://www.youtube.com/watch?v=PAFjOFxLeno&t=22s)

- 📽️ **Part 2 – Prompt tuning, escalation and testing**  
  [![Watch Part 2](https://img.youtube.com/vi/ql2kwtoTzWo/0.jpg)](https://www.youtube.com/watch?v=ql2kwtoTzWo)

Each part documents a key stage of the development and showcases how to design grounded, helpful and branded conversational AI with Copilot Studio.

---

## 🚀 Key Features

- 👋 Welcome message with markdown formatting and emojis  
- 📎 Quick reply prompts for smooth user onboarding  
- 📚 Accurate citations from trusted documents and URLs  
- 🧠 No hallucinations: general AI knowledge disabled  
- 🔓 Fully anonymous public access enabled  
- 📊 Built-in analytics to monitor usage and improvement areas  

---

## 🎓 What I learned

> This was not just a technical challenge — it was a storytelling and design journey.

From understanding **Copilot orchestration**, to creating the right tone and adapting the UX, this agent became a real showcase of how **GenAI** and **Copilot Studio** can deliver production-ready assistants for real-world use.

---

## 🧠 Want to try it yourself?

> Head over to [Copilot Studio](https://copilotstudio.microsoft.com) and start creating your own assistant!

If you want to use `tAilor` as a template or explore the export, feel free to check the `export/` folder.

---

## 👩‍💻 Author

**Araceli Fradejas Muñoz**  
Power Platform enthusiast · AI Strategist · Customer Experience Advocate  
[LinkedIn](https://linkedin.com/in/aracelifradejas) | [Medium](https://medium.com/@araceli.fradejas) | [GitHub](https://github.com/AraceliFradejas)

---

## 🏁 Let’s make AI helpful, grounded, and human — one agent at a time.
