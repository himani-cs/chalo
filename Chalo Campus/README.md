# Chalo Campus

**Going out? Don't go alone.**

Chalo Campus is a campus-focused social planning website where college students can discover activities, host plans, and meet other students from their college. Whether it’s chai, football, cafés, movies, or a walk, Chalo makes it easier to find people to go with.

> **Project status:** Front-end prototype / preview. The current version stores data in the browser and simulates certain flows. It is not yet connected to a production backend, real email verification, or live emergency-alert services.

## Features

- **Discover campus plans** — browse activities and plans, with categories and plan details.
- **Host a plan** — create a plan by choosing an activity, venue, time, group size, and other preferences.
- **Join a plan** — view who is going and join plans that have available spots.
- **Plan details** — see participants, manage your participation, and access group-related actions.
- **Student profile** — manage profile information, interests, trusted contact details, and view plans you host or have joined.
- **Safety-focused design** — includes community guidelines, reporting flows, check-in and SOS interface concepts, and options intended to encourage meetups in public places.
- **Venue information** — a page explaining how venues and hosts could work with Chalo Campus.
- **Responsive interface** — designed to work across desktop and mobile screen sizes.

## Pages

| File | Description |
|---|---|
| `index.html` | Landing page and introduction to Chalo Campus |
| `plans.html` | Browse available campus plans |
| `create.html` | Create and preview a new plan |
| `plan.html` | View an individual plan and its details |
| `me.html` | User profile, interests, hosted/joined plans, and trusted contact |
| `safety.html` | Safety features and guidance |
| `legal.html` | Community rules, privacy notice, and terms |
| `venues.html` | Information for venues and hosts |

## Getting started

The project is a collection of static HTML pages, so no package installation or build step is required.

### Run locally

1. Download or clone this repository.
2. Keep all the HTML files in the same directory.
3. Open `index.html` in a web browser.

For a local development server, you can use the VS Code **Live Server** extension, or run:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage` for prototype data persistence
- Google Fonts for typography

There is no framework, package manager, or build pipeline required for the current prototype.

## How the preview works

- Sample plans are included so the interface can be explored immediately.
- Plans and user-generated prototype data are stored in the browser using `localStorage`.
- Data is local to the browser and device where the website is opened; it is not shared between users or synced to a server.
- The student sign-up and email-code verification flow is simulated. No verification email is sent; the preview accepts any six-digit code.
- SOS and trusted-contact alert actions are interface demonstrations only. They do not send messages or contact emergency services.
- Waitlist entries are stored locally in the browser and are not submitted to a mailing list or server.

**Important:** Do not use the prototype as a real student-verification, communication, or emergency-response system. The safety interfaces are concepts for a future production implementation, not a substitute for emergency services. In India, call **112** for emergency assistance.

## Deployment

Because this is a static website, it can be hosted using GitHub Pages or any static web-hosting service.

### GitHub Pages

1. Push the project files to a GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you want to publish (usually `main`) and the repository root (`/`).
5. Save. GitHub Pages will provide the published website URL once deployment is complete.

Make sure `index.html` is in the published root directory.

## Future improvements

- Backend and database integration for shared plans and profiles.
- Real college-email verification and secure authentication.
- Live group chat and participant updates.
- Functional trusted-contact notifications and emergency workflows.
- Server-side reporting, moderation, and abuse prevention.
- Venue onboarding, booking integrations, and payment handling.
- Stronger privacy, security, and data-retention controls.

## Contributing

Contributions, ideas, and feedback are welcome. For substantial changes, consider opening an issue first to discuss the proposed improvement.

## Disclaimer

Chalo Campus is a prototype intended for demonstration and development. Features described as preview or simulated should not be treated as live services. Do not enter sensitive personal information into this prototype.

---

Made with the idea that campus plans are better together.  
**Chalo Campus**
