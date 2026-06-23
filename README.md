# TraceBack – Smart Lost and Found Portal

this is our project for the semester – a smart lost and found portal called **TraceBack**.  
the idea came from the fact that losing stuff on campus is super annoying and there's no proper system to recover it.

---

## what does it do

basically if you lost something (wallet, keys, phone etc) you can report it here.  
if someone found something they can report that too.  
the system then tries to match them using AI and shows a confidence score.  
if match is found, the finder and owner can connect and collect the item from near the parcel area.

---

## tech stack

we planned and are building this using:

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

## what's working in this prototype

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

## how to run

just open `index.html` in chrome or any browser. no setup needed for the prototype.

for the full backend setup (FastAPI + SQLite) — that's in a separate branch (coming soon).

---

## folder structure

```
traceback-portal/
├── index.html      (complete frontend prototype)
├── README.md       (this file)
└── LICENSE         (MIT)
```

---

## pickup & contact info

when a match is found the user gets:
- a 10 digit contact number of the finder
- pickup location: near parcel area, main gate – security desk
- helpline: 1800-123-4567 (toll free)

---

## team

**Kushagra Yadav**  
kushagra.24bai10536@vitbhopal.ac.in  
VIT Bhopal University

**Vinit Agarwal**  
vinit.24bmr10007@vitbhopal.ac.in  
VIT Bhopal University

---

## license

MIT License – see LICENSE file
