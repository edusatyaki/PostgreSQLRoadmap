# PostgreSQL Practice Roadmap

121 curated SQL problems (LeetCode + PGExercises) across 10 topics, easy → hard.

## Live app (GitHub Pages)
The static frontend is served from GitHub Pages and stores progress in a Google Sheet
via a Google Apps Script Web App (`Code.gs`).

- `index.html` — the app (Pages build; posts to the Apps Script `/exec` endpoint).
- `Code.gs` — Apps Script backend bound to the Google Sheet (`doGet` serves the
  Apps-Script-hosted copy; `doPost` is the JSON API the Pages build calls).

Progress is stored per student keyed by **enrolment number** (Section, Lab, Name, LastIP,
and one column per problem). Also cached locally in the browser (IndexedDB) for offline use.

---
Developer & roadmap generator — **Satyaki Das** · M.Tech, Jadavpur University
