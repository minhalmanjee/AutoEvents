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
├── index.html # Main application UI
├── style.css # TailwindCSS (via CDN)
├── script.js # Core logic (batch upload, API calls, calendar export)
└── README.md # Project documentation

## ⚡ How It Works  
1. Upload one or more event flyers (images).  
2. The system hashes files to avoid duplicates.  
3. Flyers are sent to **Google Gemini AI** for structured data extraction.  
4. Users review/edit extracted details in a form.  
5. Export all events as a `.ics` file and add them to a calendar app.  

---

## 🎯 Problem This Solves  
Event organizers and attendees often have to manually input details from flyers into calendars.  
This tool automates the process, **saving time, reducing errors, and improving productivity**.  

---

## 🚧 Future Enhancements  
- OCR fallback for non-text flyers  
- Multi-language flyer support  
- Direct integration with Google Calendar API  
- Event categorization & tagging  


---

# 📌 Resume Project Entry (Showcasing PM Skills)

**Event Snap – Batch Event Scanner**  
*Personal Product Initiative | 2025*  
- **Identified a gap** in event management where users waste time manually adding details from flyers into calendars.  
- **Designed and built** a full-stack prototype that enables users to **upload, scan, deduplicate, and export events in bulk** using AI-powered extraction.  
- **Streamlined UX** with step-by-step states (upload → preview → review → export), improving clarity and usability.  
- **Integrated AI (Google Gemini API)** to automate extraction of event data from flyers, reducing manual input errors.  
- **Delivered an MVP** that works cross-platform (desktop & mobile) and exports directly into calendar apps, saving users hours of repetitive work.  
- Skills: **Product Management, Problem-Solving, User-Centered Design, AI Integration, Rapid Prototyping, Initiative & Ownership**  

---

Would you like me to also **rewrite this as a LinkedIn project post** (storytelling style, showing initiative & problem-solving) so it doubles as a portfolio piece?

