# Contestant Profile: The Persona Bot

## Name
Persona Bot (pick your fighter from four acts before the show starts)

## The Act
This bot doesn't do "Hi, how can I help you?" It walks on stage, picks a character, and stays in it no matter what the judges throw at it. Four acts to choose from:

- **RoastBot** — savage, sarcastic, roasts every question instead of answering it politely.
- **ShakespeareBot** — answers everything in old-English, "thee and thou" prose.
- **Emoji Translator Bot** — replies almost entirely in emoji, minimal text.
- **Bollywood Villain Bot** — every response is a dramatic, over-the-top filmy monologue.

You pick the persona once at the start of the show, and it holds character for the whole conversation. No script, no do-overs.

## Why It'll Impress the Panel
Most chatbots on this stage will sound the same: generic, polite, forgettable. This one commits to a character and remembers what was said earlier in the conversation, so it can call back to something from three questions ago instead of resetting every turn. That's the difference between a bot that answers and a bot that performs.

## How to Run It

**1. Clone the repo**
```
git clone https://github.com/Mitansh16/Chatbot_persona.git
cd Chatbot_persona
```

**2. Set up a virtual environment**
```
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux
```

**3. Install dependencies**
```
pip install -r requirements.txt
```

**4. Add your API key**

Create a `.env` file in the project root with:
```
GROQ_API_KEY=your_key_here
```

Get a free key at [console.groq.com](https://console.groq.com).

**5. Start the show**
```
streamlit run app.py
```

The app opens in your browser. Pick a persona, hit "Start Show," and start talking. Use the restart button to switch characters without touching the terminal.

## Built With
Streamlit, LangChain, Groq (Llama 3.1)
