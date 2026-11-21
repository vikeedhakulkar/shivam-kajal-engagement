# Shivam ❤️ Kajal — Engagement Celebration Website
**Date:** Sunday, 13 December 2026  
**Location:** Mumbai, Maharashtra, India  
**Theme:** Royal Pastels, Gold Foil & Romantic Indian Whimsy

---

## 🌟 Highlights & Features
This web application is a faithful, enhanced reconstruction based on the design language of `https://yash-monika-shaadi-spark.lovable.app/`, customized for **Shivam & Kajal's Engagement**:

1. **Auspicious Sanskrit Blessing**: `॥ ॐ श्री गणेशाय नमः ॥` and `॥ शुभ सगाई ॥` in Tiro Devanagari Hindi calligraphy.
2. **Opening Intro Preloader**: Elegant pulsing "S ❤️ K" monogram with soft invitation reveal.
3. **Royal Arch Hero**: 3D Pixar/Disney style couple illustration framed with gold arch, floral borders, floating heart stickers, and a shimmering "Enter Our Engagement World" CTA button.
4. **Floating Rose Petals Engine**: Canvas-based continuous drifting and fluttering rose petals.
5. **Interactive Gold Scratch Card**: Realistic gold foil canvas that guests can scratch using touch or mouse cursor to reveal the date announcement and trigger a festive confetti explosion.
6. **Live Countdown Timer**: Real-time ticker counting down days, hours, minutes, and seconds to **13 December 2026, 10:30 AM IST**.
7. **Our Story Polaroid Timeline**: Milestone line with tilted polaroids, washi tape accents, and cursive captions detailing Chapter 1 (*The Beginning*), Chapter 2 (*The Proposal*), and Chapter 3 (*Forever Starts Here*).
8. **Daytime Engagement Functions Grid (Traditional Sagai)**:
   - **Function 01**: Swagat & Refreshments — Floral welcome with bouquet greeting (10:30 AM onwards)
   - **Function 02**: Puja, Tilak & Ring Ceremony — Sacred rituals & diamond rings (11:45 AM)
   - **Function 03**: Shagun, Aashirwad & Sangeet — Blessings, family dances & music (1:00 PM onwards)
   - **Function 04**: Shahi Bhoj & Royal Feast — Grand afternoon culinary feast (1:45 PM – 4:30 PM)
9. **Photo Gallery & Lightbox**: Interactive grid of moments with full-screen lightbox modal and arrow key navigation.
10. **RSVP Form with Local Persistence**: Instant guest RSVP submission, celebratory confetti, and a built-in guest list viewer for the couple.
11. **Venue & Directions**: Embedded Google Maps with one-click "Get Directions" and "Open in Maps" buttons for Mumbai.
12. **Romantic Ambient Music**: Built-in soothing Indian flute / shehnai synthesizer with interactive play/pause button and audio equalizer bars.
13. **Social Sharing**: "Add to Google Calendar" and "Share on WhatsApp" pre-configured buttons.

---

## 🚀 How to Run & Preview

### Option 1: Direct Browser Launch (No server required!)
Simply double-click or open `engagement-website/index.html` directly in any web browser (Google Chrome, Microsoft Edge, Safari, Firefox). All styling, scripts, and downloaded artwork load locally out of the box.

### Option 2: Local HTTP Server
Run in this directory:
```bash
npx serve -l 3000 .
```
Then visit `http://localhost:3000` in your browser.

---

## 🎨 Asset Structure
```
engagement-website/
├── index.html                     # Main interactive application
├── package.json                   # Project configuration & start script
├── README.md                      # Documentation & guide
└── assets/                        # High-resolution 3D illustrations
    ├── couple-hero.jpg            # Hero royal portrait
    ├── couple-bouquet-welcome.jpg # Function 01 (Swagat & Bouquet Greeting)
    ├── couple-ring-ceremony.jpg   # Function 02 (Sagai & Ring Exchange)
    ├── couple-reception.jpg       # Function 03 (Sangeet & Celebrations)
    ├── couple-engagement-feast.jpg# Function 04 (Shahi Bhoj & Feast)
    ├── story-beginning.jpg        # Chapter 1 (Where it began)
    ├── story-moment.jpg           # Chapter 2 (She said yes!)
    ├── story-forever.jpg          # Chapter 3 (13.12.2026)
    └── couple-wave.jpg            # Footer waving avatar
```

---

## 💌 Live Google Sheets RSVP Backend
The website is connected to a live Google Sheet via a Google Apps Script Web App:
- **Webhook Endpoint:** Configured in `index.html` (`GOOGLE_SCRIPT_URL`)
- **Row Columns:** `Timestamp (IST)`, `Guest Name`, `Mobile Number`, `Attending`, `Guests`, `Personal Message`
- **Features:** 
  - Real-time guest recording directly into Shivam & Kajal's Google Drive.
  - Zero database pausing/sleeping (100% online up to December 2026).
  - Built-in loading spinner, guest count selector (1–6+), personalized confirmation message, and celebratory confetti.
  - Privacy-preserving guest list modal with phone number masking (`98••••••10`).

---

## 🌐 Free 1-Click Deployment (Vercel & GitHub)
To share this website with guests on WhatsApp, Instagram, or email:
- **Vercel (Recommended)**: 
  1. Import the `shivam-kajal-engagement` repository on [vercel.com](https://vercel.com).
  2. If deploying from the root repository, set **Root Directory** to `engagement-website` (or leave default if the repository root contains `index.html`).
  3. Deploy! Vercel automatically deploys static assets with configured `vercel.json` routing.
- **GitHub Pages**: Push this folder to your GitHub repository, enable GitHub Pages in Repository Settings -> Pages, and it will be live immediately.
