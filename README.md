# SafeRoute AI 🎯
#Basic Details

### Team Name: Code Crafters

### Team Members
- Member 1: Rajeswary M G - Adi Shankara Institute of Technology and Engineering
- Member 2: Sania Joby - Adi Shankara Institute of Technology and Engineering

### Project Description
SafeRoute AI is a web app that suggests the safest walking route — not just the shortest — using crowd-reported unsafe zones, streetlight availability, time-based safety scoring, and nearby police stations.

### The Problem Statement
People, especially women and students, often navigate through unsafe streets without knowing which routes are risky — particularly at night. Existing maps only optimize for speed, not safety.

### The Solution
SafeRoute AI assigns an AI-powered Safety Score (0–100) to every street using real-time data — lighting maps, crowd reports, crime history, and police proximity — and routes users through the safest path. A one-tap emergency alert shares live location with contacts and local police.

### Hosted Project Link
https://saniajoby.github.io/saferoute2/

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: HTML, CSS, JavaScript
- Frameworks used: None (Vanilla JS)
- Libraries used: Google Fonts (Space Mono, Syne)
- Tools used: VS Code, GitHub Pages

---

## Features

- 🤖 **AI Safety Score** — Every street rated 0–100 in real time
- 👥 **Crowd-Reported Zones** — Community flags unsafe areas
- 💡 **Streetlight Mapping** — Routes prioritize well-lit paths
- ⏱ **Time-Based Scoring** — Safety scores change by hour (day vs night)
- 🚔 **Police Station Proximity** — Routes near police stations weighted higher
- 🆘 **One-Tap Emergency Alert** — Sends live GPS to contacts + local police

---


#### Installation
```
No installation needed — open index.html directly in any browser
```

#### Run
```
# Option 1: Double-click index.html
# Option 2: Use Python server
python -m http.server 8000
# Then visit: http://localhost:8000
```

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

<img width="1885" height="949" alt="image" src="https://github.com/user-attachments/assets/88047b29-c45b-47cf-8aef-8747e516bb4c" />

<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/d2989eac-0e73-4e07-8ba5-a375d8d17f06" />
<img width="1919" height="890" alt="image" src="https://github.com/user-attachments/assets/f18e63f7-56b7-4f32-b840-4c31df57bce0" />
<img width="1916" height="880" alt="image" src="https://github.com/user-attachments/assets/b07f874b-d18d-4ea8-9a89-a773f0e3da7d" />




#### Diagrams

**System Architecture:**
```
User Input (Origin + Destination + Time)
        ↓
AI Safety Scoring Engine
        ↓
[Streetlight Data] + [Crowd Reports] + [Police Proximity] + [Historical Incidents]
        ↓
Route Comparison (Safe / Moderate / Risky)
        ↓
Map Display + Street-level Score Labels
        ↓
Emergency Alert System (One-tap → Contacts + Police)
```

---

## Project Demo

### Video
[Add your demo video link here]

### Additional Demos
[https://your-username.github.io/saferoute/]

---

## AI Tools Used

**Tool Used:** Claude (Anthropic)

**Purpose:** Full frontend design and code generation

- Generated complete HTML/CSS/JS single-file web app
- Designed interactive map with SVG city grid
- Built AI Safety Score UI with animated bar charts
- Created emergency SOS modal with contact system

**Percentage of AI-generated code:** ~90%

**Human Contributions:**
- Project concept and feature ideation
- Requirement definition and problem framing
- Testing and feedback
- Documentation

---

## Team Contributions

- **Rajeswary M G**: Project concept and ideation, AI Safety Score design, 
  frontend development, interactive map implementation, 
  emergency alert system, UI/UX design

- **Sania Joby**: Feature planning and requirement definition, 
  safety filter implementation, route comparison system, 
  testing and debugging, project documentation and README



---

## License
This project is licensed under the MIT License.

---


Made with ❤️ at TinkerHub# saferoute2
