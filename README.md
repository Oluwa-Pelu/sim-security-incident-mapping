# SIM — Security Incident Mapping

A web platform for AAUA students, staff, and landlords to quickly report campus security incidents (stabbing, sexual assault, theft, murder, and other crimes), built for SEN202 Weekend Dev.

## Problem

Campus insecurity is worsened by underreporting — fear of retaliation, no centralized reporting channel, and slow response times mean many incidents go unreported or unresolved. See `docs/ishikawa.png` for the full root-cause analysis.

## Solution

SIM lets community members report incidents (optionally anonymously) through a simple web form, and gives security personnel a live, prioritized feed of reports to verify and act on.

## Repository structure

```
├── index.html          # mini web interface (report form + live incident feed)
├── docs/
│   ├── SRS.docx         # Software Requirements Specification
│   ├── usecase.png       # UML use case diagram
│   └── ishikawa.png      # Ishikawa (fishbone) problem analysis
└── README.md
```

## Running it

Open `index.html` in any browser — no build step or server required. It's a single-page prototype using vanilla HTML/CSS/JS with in-memory state (no backend yet).

## Author

Obajide Pelumi (Matric No: 241201174) — Computer Science, Adekunle Ajasin University, Akungba-Akoko.

## Course

SEN202 — Weekend Dev, Weekend 1 (01/07/26). Supervisor: Dr. O. O. Ajayi.
