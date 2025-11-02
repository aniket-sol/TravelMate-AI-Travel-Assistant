# 🧳 TravelMate — AI Travel Assistant (CLI)

**TravelMate** is a simple yet powerful **command-line chatbot** built in Python that helps users with **travel-related questions and trip planning**.  
It uses the **Groq API** with the **LLaMA 3.3 70B** model to deliver fast, intelligent, and conversational travel advice — all from your terminal.

---

## ✨ Features

- 💬 **Interactive CLI Chat** — Talk directly with the bot via your terminal.  
- 🌍 **Global Travel Knowledge** — Get insights on destinations, attractions, transport, and safety.  
- 🧳 **Trip Planning Help** — Receive personalized itineraries and travel suggestions.  
- 🏨 **Accommodation & Transport Advice** — Find best options suited to your budget or style.  
- ♻️ **Ethical & Sustainable Travel Tips** — Encourages responsible and respectful travel.  
- 🔒 **Privacy Respectful** — No data collection or personal information storage.

---

## 🧰 Tech Stack

- **Language:** Python 3.8+  
- **Libraries:**  
  - [`groq`](https://pypi.org/project/groq/) — for interacting with the Groq API  
  - [`python-dotenv`](https://pypi.org/project/python-dotenv/) — for environment variable management  
- **Model:** `llama-3.3-70b-versatile`

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/travelmate-cli.git
cd travelmate-cli
```

### 2️⃣ Set Up a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install groq python-dotenv
```

### 4️⃣ Add Your API Key
Create a .env file in the project root:
```bash
GROQ_API_KEY=your_groq_api_key_here
```
You can get your API key from Groq’s developer portal.

### 5️⃣ Run the Chatbot
```bash
python travelmate.py
```

Example session:
```bash
🤖 AI Travel Assistant (type 'exit' to quit)
You: Tell me about Japan
AI: 🇯🇵 Japan offers a perfect blend of ancient tradition and modern innovation...
Would you like me to suggest a 5-day itinerary?
```

📁 Project Structure
```bash
travelmate-cli/
│
├── travelmate.py        # Main chatbot script
├── .env                 # Contains your Groq API key (not committed)
└── README.md            # Project documentation
```

---

## 🧠 How It Works

1. Loads your Groq API key from .env

2. Sets up a system prompt that defines the assistant’s personality and rules

3. Accepts user input and sends it to the Groq API

4. Displays the assistant’s response in the terminal

5. Continues conversation until you type exit

💡 Example Interactions
```bash
You: Suggest me some budget-friendly destinations in Europe.
AI: 💶 Sure! Here are a few affordable European destinations:
    - Budapest, Hungary
    - Lisbon, Portugal
    - Krakow, Poland
Would you like me to create a 7-day itinerary for one of them?
```

```bash
You: What’s the weather like in Bali this time of year?
AI: 🌴 Bali in November is warm and humid, averaging 30°C with occasional rain showers.
It's still great for beach activities and cultural sightseeing.
```
---

## 🔮 Future Enhancements

-> Add live web search integration for up-to-date visa or event info

-> Save chat logs or export itineraries

-> Build a simple GUI or web version

-> Support multiple languages

---

## 🤝 Contributing

1. Contributions are welcome!

2. Fork the repo

3. Create a new branch (git checkout -b feature/new-feature)

4. Commit your changes (git commit -m 'Added new feature')

5. Push to the branch (git push origin feature/new-feature)

6. Create a Pull Request

---

## 🧾 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

---

## 💬 Acknowledgements

Groq API for powering the LLaMA 3.3 model

The open-source Python community 🐍

Travel enthusiasts worldwide 🌍
