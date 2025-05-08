🤝 aimSessionFour

An LLM-powered chatbot that negotiates Facebook Marketplace listings on your behalf.

💡 What It Does

aimSessionFour is a Python-based assistant powered by a local LLM (e.g., phi3:mini via Ollama) that helps you craft friendly, polite, and effective negotiation messages for Facebook Marketplace. It takes key information about the item and generates a message that:

Expresses interest

Politely asks if the price is negotiable

Offers a respectful counter-offer

Optionally asks a clarifying question

🧠 Tech Stack

Python

Ollama – for running local LLMs like phi3:mini

LLM Prompt Engineering – designed for casual, human-sounding negotiation

🚀 How to Use

Install Ollama👉 https://ollama.comPull the model you want to use (e.g., phi3:mini)

ollama pull phi3:mini

Start Ollama

ollama serve

Run the bot script

python negotiate.py

Input listing details when prompted (name, description, price, platform)

Get your message and paste it into Facebook Marketplace!

📦 Example Output

💬 Suggested Message:
Hey! I’m interested in the [item name] — is the price negotiable at all? Would you consider something closer to $XX? Just curious, is there any damage or issue not listed?

🛠 Current Limitations

Requires a running instance of Ollama at localhost:11434

Runs in the terminal (no UI yet)

🔮 Future Plans

Chrome Extension – Work in ProgressI'm exploring how to turn this bot into a Chrome extension that:

Lets users paste listing details directly

Generates negotiation messages instantly⚠️ However, I'm currently running into issues connecting Chrome Extensions to Ollama locally due to CORS and networking constraints. A different approach will be needed.

🙏 Contributions Welcome

Feel free to fork, improve, or create pull requests.If you’re interested in helping solve the Chrome Extension + local LLM connection problem — I’d love to collaborate!

📄 License

MIT

