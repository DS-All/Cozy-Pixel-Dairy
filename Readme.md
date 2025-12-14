# 📖 Cozy Pixel Diary

Cozy Pixel Diary is a browser-based personal journaling application designed with a pixel-art inspired interface.  
It runs entirely on the client side, works offline, and stores all entries locally in the browser.

---

## Overview

This project recreates the experience of writing in a physical diary using a book-style layout, soft animations, and warm visual design.  
Each diary entry is organized by date and can include text, mood indicators, images, and printable exports.

The application requires no installation, backend, or external libraries.

---

## Features

### Book-Style Interface
- Two-page diary layout
- Page-turn animations using CSS 3D transforms
- Animated open and close transitions
- Paper-textured pages and pixel-styled controls

### Daily Entries
- One entry per calendar date
- Automatic date handling
- Navigation between previous and next days
- Jump navigation to the nearest existing entries

### Writing & Mood Tracking
- Distraction-free writing area
- Emoji-based mood (vibe) selector
- Mood stored per entry
- Mood information included in exports

### Image Attachments
- Attach up to three images per entry
- Pixel-rendered image display
- Remove images individually
- Images stored locally using Base64 encoding

### Cover Customization
- Editable diary title and subtitle
- Persistent storage of cover text
- Decorative text customization
- Live updates on the book cover

### Offline Storage
- Uses browser LocalStorage
- No network access required
- No user accounts or authentication
- Data persists between sessions

### Export
- Export individual entries as printable pages
- Includes date, mood, text, and images
- Uses native browser print functionality

---

## Technology

- HTML5 for structure
- CSS3 for layout, animations, and visual design
- Vanilla JavaScript for application logic
- Browser LocalStorage for persistence

No frameworks, build tools, or external dependencies are used.

---

## File Structure
index.html <br>
├── Embedded CSS <br>
│ ├── Layout and theming <br>
│ ├── Book and page animations <br>
│ └── Visual effects <br>
└── Embedded JavaScript <br>
├── Entry state management <br>
├── Date navigation <br>
├── Image handling <br>
├── LocalStorage persistence <br>
└── Export functionality <br>

---

## Usage

1. Open `index.html` in a modern web browser.
2. Click the diary book on the home screen.
3. Write your entry for the selected date.
4. Optionally select a mood and attach images.
5. Save the entry or export it as a printable document.

---

## Data Storage

Each diary entry is stored using a date-based key: diary-[Date String]

Stored entry data includes:
- Text content
- Selected mood
- Attached images

Cover metadata is stored separately for reuse across sessions.

---

## Privacy

- All data is stored locally in the browser
- No data is transmitted or collected
- No third-party services are used

Clearing browser storage will remove all entries.

---

## Compatibility

- Works in all modern desktop browsers
- Requires JavaScript enabled
- Best experienced on larger screens

---

## Author

Danish Shaikh  
GitHub: https://github.com/DS-All  
LinkedIn: https://www.linkedin.com/in/ds-all  
Instagram: https://www.instagram.com/ds_all_official/

---

## License

MIT License  
This project is free to use, modify, and distribute.

