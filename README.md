**EVA — Virtual Assistant**

A browser-based virtual assistant built with HTML, CSS, and vanilla JavaScript. It supports both voice and text commands, and integrates with free public APIs for real-time information.

![status](https://img.shields.io/badge/status-active-brightgreen)
![license](https://img.shields.io/badge/license-MIT-blue)

**Features**

-  Voice input — via the browser's Web Speech API (`SpeechRecognition`)
-  Voice output — via `SpeechSynthesis` (text-to-speech)
-  Live weather for any city (Open-Meteo API — no key required)
-  Wikipedia summaries for any topic
-  Random jokes (JokeAPI)
-  Basic calculator ("calculate 12 * 4 + 1")
-  Web search shortcut ("search cute cats")
-  Quick launch for YouTube

**Project Structure**

```
virtual-assistant/
├── index.html      # App markup / structure
├── style.css        # Styling and layout
├── script.js         # Assistant logic, speech, and API calls
├── README.md         # Project documentation
└── LICENSE            # MIT license
```

**Getting Started**

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/virtual-assistant.git
   cd virtual-assistant
   ```
2. Open `index.html` directly in a browser, **or** serve it locally:
   ```bash
   npx serve .
   ```
3. Click the 🎤 button and grant microphone permission, or just type a command in the input box.

> Note: Voice recognition (`SpeechRecognition`) currently works best in Chrome and Edge. Text input works in every modern browser.

**Example Commands**

| Say / Type                     | Response                              |
|---------------------------------|----------------------------------------|
| "What's the time?"              | Speaks the current time                |
| "Weather in Tokyo"              | Live temperature and wind speed        |
| "Tell me a joke"                | Random joke                            |
| "Wikipedia machine learning"    | Short Wikipedia summary                |
| "Calculate 25 * 4"              | Evaluates the expression               |
| "Search best laptops 2026"      | Opens a Google search in a new tab     |

**Built With**

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- Web Speech API
