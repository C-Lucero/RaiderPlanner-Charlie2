# Raider Planner

**Team:** Charlie2
**App Type:** Academic Calendar / Planner

## About

Raider Planner combines many academic tools into one website. It targets common pain points college students run into with planning, attending, understanding, and remembering what they need to do to be successful in college. Instead of jumping between separate sites for schedules, course searches, study groups, and degree plans, students can manage all of it in one place.

## Pages

| Page | File | Description |
|------|------|-------------|
| Calendar | `index.html` | Main calendar page where you can add any TTU course by CRN, as well as any custom event of your choosing. |
| Course Search | `search.html` | Search for TTU courses by term, department, or keyword. |
| Class Connect | `social.html` | Social page used to connect with other students and form study groups. |
| Plans & Export | `plans.html` | Manage multiple schedule variations, export your calendar to external apps, or batch-import registration CRNs. |
| Degree Roadmap | `roadmap.html` | Map your degree plan across all four years. Visualizes your course load across your academic career and shows the prerequisites you need to take. |

## Key Interactive Features

1. **Interactive calendar:** A calendar (loaded from a CDN) that displays your courses and custom events.
2. **Course search:** Filter TTU courses by term and department to find classes.
3. **Social profiles:** Create and save your social profile to share with other students.
4. **Batch CRN import:** Paste a comma-separated list of CRNs to add multiple courses to your calendar at once.
5. **Plan ahead:** Import different courses into separate schedule plans and plan future semesters.

## Project Structure

```
RaiderPlanner-Charlie2/
├── index.html
├── search.html
├── social.html
├── plans.html
├── roadmap.html
├── images/
│   └── ttulogo.png
└── static/
    └── css/
        └── style.css
```

## Built With

- **HTML5:** Semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- **CSS3:** One shared external stylesheet (`static/css/style.css`) using Flexbox, CSS Grid, and media queries for responsive design
- **Git & GitHub:** Version control, with each team member working on their own branch and merging through pull requests

## How to View

1. Clone the repo:
   ```bash
   git clone https://github.com/C-Lucero/RaiderPlanner-Charlie2.git
   ```
2. Open `index.html` in your browser.
3. Use the nav bar to move between pages.

## Team Members

| Name | Page |
|------|------|
| Zeke Garcia | Calendar (`index.html`) |
| Phoenix | Course Search (`search.html`) |
| Huddy | Class Connect (`social.html`) |
| Christopher Lucero | Plans & Export (`plans.html`) |
| Noah | Degree Roadmap (`roadmap.html`) |
