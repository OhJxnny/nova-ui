# nova-ui

## Beschreibung
Dies ist das Frontend für meine persönliche KI: `nova_core`.  
`nova-ui` ist eine progressive WebApp (PWA), die auf dem iPhone läuft und als Interface für meine eigene, lokal oder remote gehostete LLM-Instanz dient.

Ziel ist es, eine minimalistische, mobile-freundliche Oberfläche zu bauen, die Kamera-, Mikrofon- und Texteingabe unterstützt. Die App soll in Echtzeit mit meiner KI kommunizieren, die Antworten anzeigen oder sprechen und langfristig als HUD genutzt werden können.

---

## Features (geplant)
- ✅ Chat mit lokalem LLM (via API)
- 🎙 Spracheingabe über Mikrofon (Whisper-Integration geplant)
- 📷 Kamera-Funktion für Vision-Eingabe (z. B. GPT-4o oder lokale Vision-Module)
- 💬 Ausgabe als Text, später auch per Text-to-Speech
- 📱 100 % mobilfreundlich (iPhone First), offlinefähig als PWA
- 🧠 Verbindung zu `nova_core` über lokale API

---

## Technischer Stack
- **Frontend**: React (Vite)
- **Design**: Mobile-first, dunkles Theme, HUD-kompatibel
- **API**: JSON-Exchange mit `nova_core`
- **Deployment**: Optional als PWA auf iOS (Homescreen-Mode)

---

## Setup
```bash
# Lokale Entwicklung
npm install
npm run dev