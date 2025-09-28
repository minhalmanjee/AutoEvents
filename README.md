# AutoEvents
# 📸 Event Snap - Batch Scanner  

Event Snap is a lightweight web app that lets users **batch upload, scan, and extract event details from multiple flyers** at once. It automatically parses flyer content into structured event data (title, date, time, location, description) and allows users to **add all events directly to their calendar** in a single click.  

---

## 🚀 Features  
- **Batch Upload & Preview** – Select multiple flyers, preview them, and avoid duplicates.  
- **AI-Powered Event Extraction** – Uses Google Gemini API to extract event details in structured JSON.  
- **Smart Deduplication** – Prevents duplicate flyers and duplicate events.  
- **Editable Forms** – Review & confirm extracted event details before adding.  
- **One-Click Calendar Export** – Download events as `.ics` and add to Google Calendar, iCal, or Outlook.  
- **Cross-Platform** – Works seamlessly on mobile (Android & iOS) and desktop browsers.  

---

## 🛠️ Tech Stack  
- **Frontend:** HTML, TailwindCSS, JavaScript  
- **AI Integration:** Google Gemini API (Vision + Text Extraction)  
- **File Handling:** SHA-256 hashing for duplicate detection  
- **Calendar Export:** ICS file generation for universal compatibility  

---

## 📂 Project Structure  
