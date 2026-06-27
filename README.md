# TraceBack – Smart Lost and Found Portal

This is our project for the semester – a smart lost and found portal called **TraceBack**.  
The idea came from the fact that losing stuff on campus is super annoying and there's no proper system to recover it.

---

## What does it do

Basically if you lost something (wallet, keys, phone etc) you can report it here.  
If someone found something they can report that too.  
The system then tries to match them using AI and shows a confidence score.  
If match is found, the finder and owner can connect and collect the item from near the parcel area.

---

## Tech stack

We planned and are building this using:

- **Frontend** – HTML, CSS, Vanilla JavaScript (this repo is the UI prototype)
- **Backend** – FastAPI (Python) — handles the API calls and matching logic
- **AI / ML** – TensorFlow — for image-based feature extraction and matching
- **Database** – SQLite — stores item reports, user data, match records
- **Mobile** – Flutter — for the mobile version (planned)
- **Auth & Realtime** – Firebase — for login and live notifications

> right now this repo has the complete frontend prototype.  
> the FastAPI backend and TensorFlow model are being integrated separately.  
> we built the UI first so we could show the full user flow clearly.

---

## What's working in this prototype

- landing page with how it works section
- report lost item form
- report found item form  
- AI scan animation with confidence score (simulated for prototype)
- search registry with real-time filter (type watch → searches watches only)
- match results page with contact number and pickup location
- collapsible sidebar
- time based greeting (good morning / evening etc)
- messages, notifications, profile pages
- my reports section

---

## How to run

just open `index.html` in chrome or any browser. no setup needed for the prototype.

for the full backend setup (FastAPI + SQLite) — that's in a separate branch (coming soon).

---

## Folder structure

```
traceback-portal/
├── index.html      (complete frontend prototype)
├── README.md       (this file)
└── LICENSE         (MIT)
```

---

## Pickup & contact info

when a match is found the user gets:
- a 10 digit contact number of the finder
- pickup location: near parcel area, main gate – security desk
- helpline: 1800-123-4567 (toll free)

---

## Team

**Kushagra Yadav**  
kushagra.24bai10536@vitbhopal.ac.in  
VIT Bhopal University

**Vinit Agarwal**  
vinit.24bmr10007@vitbhopal.ac.in  
VIT Bhopal University

---

## License

MIT License – see LICENSE file
