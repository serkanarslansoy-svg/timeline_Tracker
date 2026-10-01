# Martur Italy — Timeline

Engineering schedule for the Torino plant. No install.

Open `index.html`. The Martur Italy mark is embedded in the page.

- Opens on a project overview: every project as a card with its status, window and a mini timeline
- Pick a project to open its Gantt chart, task list and board
- Drag a bar to move a phase; drag either end to extend or shorten it
- ISO weeks, W36 2026 through W35 2027 (including W53 of 2026)
- Download a project, or all projects, as an A4 landscape PDF Gantt chart
- Light, dark and automatic (system) theme
- Works as a phone app: bottom tab bar, bottom sheets, tap a bar to edit, press and hold to drag
- Installable (PWA) with an offline cache once it is served over https
- Stored in this browser. Export or import a JSON backup

PDF export loads jsPDF from a CDN the first time it is used, so it needs an internet
connection. Names with characters outside Western European Latin (for example
Turkish ş, ğ, ı) also load the DejaVu Sans font so they print correctly.

## On a phone

The app installs from any https address. With GitHub Pages:

1. Repository **Settings → Pages → Build and deployment**: Source *Deploy from a branch*,
   branch `main` (or the branch you want to publish), folder `/ (root)`, **Save**.
2. Open `https://serkanarslansoy-svg.github.io/timeline_Tracker/` on the phone.
3. Android (Chrome): tap **Install** in the banner, or menu → *Install app*.
   iPhone (Safari): Share → *Add to Home Screen*.

Plans are stored per browser, so a phone starts with the sample plan. Use
**Export backup** on the computer and **Import** on the phone to bring your projects over.
