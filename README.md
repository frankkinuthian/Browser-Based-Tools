# Frank's Browser-Based Tools

Welcome! This project is a collection of practical, privacy-friendly browser-based utilities that run entirely on your device—no installs, no tracking, just useful tools you can trust.

---

## What is This Project?

Frank's Browser-Based Tools is a suite of web tools forked from ThioJoe designed to be:

- Local-first: Everything runs in your browser, so your data never leaves your device.
- Installable: Thanks to Progressive Web App (PWA) support, you can "install" the whole suite to your desktop or phone for offline use.
- Modern: Features like dark mode, mobile responsiveness, and a central dashboard make it easy and pleasant to use.

---

## Project Structure

Here's how the project is organized:

<pre>
Browser-Based-Tools/
├── index.html           # Dashboard homepage for all tools
├── style.css            # Shared styles (light/dark mode)
├── manifest.json        # PWA manifest (installable app)
├── service-worker.js    # PWA offline support
├── icons/               # App icons for PWA
├── Tools/               # All individual tool apps
│   ├── Unicode Inspector/
│   │   └── Unicode Inspector.html
│   └── GitHub Tools/
│       ├── Repo Explorer.html
│       └── Associated Organization Research Tool.html
└── .github/             # GitHub workflows, issue templates, project docs
</pre>

---

## Usage Instructions

1. **Open the Dashboard**

   - Open `index.html` in your browser. This is the central hub for all tools.

2. **Browse and Launch Tools**

   - The dashboard lists all available tools with descriptions and quick links.
   - Click any tool to open it in your browser.

3. **Search and Filter**

   - Use the search bar at the top of the dashboard to quickly find a tool by name or description.

4. **Toggle Dark Mode**

   - Click the "Dark Mode" or "Light Mode" button in the header to switch themes. Your preference is saved for future visits.

5. **Install as an App (PWA)**

   - In Chrome, Edge, or other modern browsers, look for the "Install" or "+" button in the address bar or browser menu.
   - The app will work offline and can be launched from your home screen or desktop.

6. **Offline Use**
   - Once installed or after the first visit, the dashboard and all tools will work offline.

---

## Dashboard

Open [`index.html`](index.html) for a central dashboard that:

- Lists all available tools with descriptions and quick links
- Lets you search/filter tools instantly
- Works great on desktop and mobile
- Offers a dark mode toggle (top right)
- Is installable as a PWA for offline use

---

## Available Tools

### [Unicode Inspector](Tools/Unicode%20Inspector/Unicode%20Inspector.html)

Paste in text and get detailed info about every character (Unicode, code points, etc.)

### [Repo Explorer](Tools/GitHub%20Tools/Repo%20Explorer.html)

Fetch and explore all repositories for a GitHub user or organization, with sorting and filtering.

### [Associated Organization Research Tool](Tools/GitHub%20Tools/Associated%20Organization%20Research%20Tool.html)

Find and verify authenticity of GitHub accounts owned by large companies, even if not officially listed.

---

## Contributing & Workflow

- Issues and feature requests use templates in `.github/ISSUE_TEMPLATE/`
- Project management follows a Kanban board (see the Projects tab)
- All code is static HTML/CSS/JS—no build step required
- See `.github/README.md` for workflow details

---

## Changelog (Recent Highlights)

- Central dashboard with search and dark mode
- PWA support: installable, offline, and mobile-friendly
- Unified look and feel across all tools
- Improved documentation and project structure

---

Thanks for visiting! If you have ideas, feedback, or want to contribute, open an issue or pull request. Enjoy the tools!
