# CSE Department Website — Multi-page static version

This is a multi-page static website for the Department of Computer Science and Engineering, IET Calicut.

## Pages

- `index.html` — Home
- `about.html` — Department profile, Vision, Mission and HOD message
- `academics.html` — Academic programmes and learning resources
- `faculty.html` — Faculty directory layout
- `research.html` — Research and student projects
- `events.html` — Events, workshops and activities
- `achievements.html` — Student, faculty and department achievements
- `placements-alumni.html` — Placements, careers and alumni
- `gallery.html` — Department gallery
- `contact.html` — Department contact information

## Run locally

Open `index.html` in a browser, or run:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Technology

- HTML, CSS and vanilla JavaScript
- GSAP + ScrollTrigger via CDN
- Responsive navigation
- Static hosting compatible (GitHub Pages, Netlify, Vercel static hosting)

## Important: verify content before publishing

The original starter template contained fictional sample statistics, people, events, projects, programme names, dates and contact details. These are not official IET Calicut information. Replace every placeholder with verified, department-approved information before publishing.

In particular, verify:
- Department name and official institutional wording
- Faculty names, designations and photographs
- HOD message and profile
- Academic programme details, syllabus and regulations
- Project titles, student teams and guides
- Event names, dates, venues and registration links
- Achievements and placement statistics
- Alumni profiles and consent
- Official address, email and telephone number

The sample faculty cards and placements/alumni sections are structural placeholders to be completed by the department.

## Editing

- Update page content in the corresponding `.html` file.
- Shared design styles are in `css/site.css`.
- Shared interactions and animations are in `js/site.js`.
- Keep navigation links consistent across all pages.
