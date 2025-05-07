# Valorant AI Coach – Tactical Voice Assistant

> 🚧 *Working Title* – Final branding TBD

This is a desktop app designed to enhance Valorant gameplay through AI-powered real-time voice callouts. It listens to live match events and responds with strategic or humorous commentary using realistic Valorant-style voices like Brimstone or Cypher.




## 🧠 How It Works

1. **Input**: Listens to live game data via [Overwolf Game Events SDK](https://overwolf.github.io)
2. **AI Processing**: Uses OpenAI to generate custom responses based on round events
3. **Voice Output**: Converts AI responses into realistic voice lines (via ElevenLabs API)
4. **Audio Playback**: Plays voice through a virtual mic (e.g. VB-Cable) so teammates hear it




## 🎥 Demo Videos

> ⚠️ These videos are for **approval demonstration purposes only**. Once full approval is received from Riot and Overwolf, live data integration and realistic in-game functionality will be implemented.

🔹 Callout Simulation (Round Start + Events)

Shows how the app simulates a Valorant round and generates tactical callouts step-by-step using mock data.

https://github.com/user-attachments/assets/a6f78bdf-e7b8-4d34-b1c1-bae82803cd32


🔹 Voice Generation Demo (Cypher Voice)

Demonstrates instant conversion of a sample callout into a realistic voice line using AI text-to-speech (Cypher voice style).

https://github.com/user-attachments/assets/e5bed02f-01a1-4925-bb22-b249affb0188





## 🔒 Compliance & Data Use

- No use of Riot's API directly  
- No game memory reading or automation  
- Fully compliant with Overwolf's SDK rules  
- Designed as an audio-only assistant (no overlays, cheats, or in-game modification)





## 📌 Tech Stack

- Node.js + Express  
- ElevenLabs API (Text-to-Speech)  
- OpenAI API (Chat/GPT generation)  
- Overwolf SDK (Game event listener)  
- VB-Audio Cable (virtual mic playback)





## 🧪 Status

Currently in early development.  
Riot API registration submitted for product compliance.




## 👨‍💻 Author

**Ayoub Basidi** – [ayoubbasidi1@gmail.com](mailto:ayoubbasidi1@gmail.com)
