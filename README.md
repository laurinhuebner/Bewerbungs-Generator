# 📑 Bewerbungs-Generator (Private WebApp)

## Überblick
Dieses Projekt ist ein **selbst entwickeltes Webtool**, das die **Erstellung von Bewerbungsunterlagen** automatisiert und gleichzeitig individuelle Anpassungen ermöglicht.  
Die Anwendung besteht aus einer **Streamlit-WebApp**, die im lokalen Netzwerk läuft, sowie einer **Android WebView-App**, die einen komfortablen mobilen Zugriff bietet.  

👉 **Hinweis:**  
Der Quellcode bleibt privat, um persönliche Daten zu schützen. Hier findest du daher nur **Screenshots**, eine Projektbeschreibung und die eingesetzten Technologien.

---

## ✨ Features
- **Anschreiben-Generator**  
- **Lebenslauf-Editor**  
- **PDF/DOCX Export**  
- **Anpassbare Vorlagen**  
- **Mobile App (Android)**  

---

## 🛠️ Technologien
- **Backend/WebApp:** [Streamlit](https://streamlit.io/) (Python)  
- **PDF/DOCX Export:** `fpdf2`, `python-docx`  
- **Deployment:** Debian Server, `systemd`  
- **Mobile Client:** Android (WebView-Wrapper)  

---

## 📸 Screenshot
*(Beispiel mit Dummy-Daten / Startansicht der App)*  

![Screenshot](screenshots/mobile.png)

---

## 🚀 Nutzung
- Die WebApp läuft **lokal im internen Netzwerk** (kein öffentlicher Zugriff).  
- Der Android-Client greift über eine feste IP (`http://192.168.x.x:8501`) darauf zu.  
- Quellcode wird nicht veröffentlicht, Projekt dient als **Proof of Concept** und **Portfolio-Referenz**.  

---

## 📂 Projektstatus
✅ Funktional im internen Einsatz  
🔒 Quellcode privat (nicht veröffentlicht)  
🖼 Screenshot & Dokumentation dienen als Showcase
