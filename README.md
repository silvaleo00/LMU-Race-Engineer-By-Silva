# LMU Race Engineer — by Silva

A virtual race engineer for **Le Mans Ultimate**. It talks to you on the radio while you race (in English, like a real engineer), answers when you press your wheel button, and shows all your data in its own Windows app.

- **Strategy and pits:** how many stops, the box lap and pit window, where you rejoin, undercut / overcut, half-price stops under full course yellow.
- **Fuel calculator:** laps in the tank, litres to the flag, how much to add at the stop, what saving 2 / 4 / 8 % gives you.
- **Tyres:** wear per tyre, laps to 75 % and 90 %, time lost per lap of age.
- **Lap times, pace and history:** every lap kept on your PC, your level (Alien → Off Pace) per track and class, every session lap by lap.
- **Analysis:** speed trace, corners, lock-ups, wheelspin, TC and ABS, track map, standings.
- **Race control:** flags, full course yellow, stopped cars, traffic.
- **AI brain (optional, free):** with a free Groq or Gemini key he understands anything you say and answers like a person, using only the real data.

In practice and qualifying he stays quiet and only answers you. In the race he calls what matters.

## The app

`LMU_Race_Engineer.exe` (or `App.bat` from Python) opens one window, no browser needed:

| Tab | What it does |
|---|---|
| Home | Start / stop the engineer, LMU status, demo race, updates |
| Race | Live strategy, fuel, tyres and lap times — Blocks, Focus or Timeline layout |
| Pace | Your level against the best known lap for the track and class |
| Sessions | Every session, lap by lap, sectors, tyres, TC / ABS |
| Analysis | Speed trace, corners, track map, standings |
| Radio & mic | Set your wheel radio button (F9 always works), pick and test the microphone |
| Voice | Pick his voice and speed, with a test |
| AI brain | Groq / Gemini / other key, model, how natural he talks |
| When he talks | Race / practice / qualifying, topics on or off |
| System | Updates, settings folder, his log |

## Getting started (players)

1. In LMU: **Settings › Gameplay › Enable Plugins: ON**.
2. Download `LMU_Race_Engineer.exe` from [Releases](https://github.com/silvaleo00/LMU-Race-Engineer-By-Silva/releases/latest), put it in a folder of its own and open it. Nothing to install.
3. *Radio & mic* → **Set wheel button**. *AI brain* → paste a free key (recommended).
4. Get on track. Press the button and ask: "fuel", "gap ahead", "strategy", "lap times"…

Windows may say "Windows protected your PC" the first time (the program is not signed): click *More info › Run anyway*. Your settings and lap history are kept next to the .exe.

## Privacy

Speech recognition uses Google (only while you hold the radio button). The online voice is Microsoft's. With an AI key, your question and the race data needed to answer go to the AI you chose. Your lap history never leaves your PC.

---

Made by **Silva** · `silva.leo` on Discord for suggestions or fixes.
