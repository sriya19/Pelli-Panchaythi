# Our little forever — Sriya & Fani

A responsive React engagement planner with original generated miniature artwork, illustrated navigation, a private invitation preview and manual approval flows.

## Development

Node 24 was used for validation.

```sh
npm ci
npm run dev
```

Vite serves port 5173. `npm run build` creates `dist`; `npm test` checks financial state transitions. Use the existing checkout in the isolated cloud environment; no extra worktree is needed.

## Data and scope

This first version saves approved records in this browser's localStorage (`sf-planner-v1`). It does not provide authentication, cross-device sync, encryption or a backend. Use Export private backup to download JSON. Do not clear browser storage without exporting. No private records or credentials are written to the source repository. No upload, messaging or public invitation publishing is implemented.

Working features: dashboard, manual add/edit/delete with preview and approval, status filtering/search, task completion celebration, cost/payment/refund tracking with duplicate checks, outfit records, generic vendor/menu/travel/activity/gift records, travel phases, editable invitation wording, event confirmation, history and last-change undo. Amounts remain unknown unless supplied; the initial INR 16,100 is only the two known outfit purchases. No payments or bookings are invented.

AI interpretation, file/receipt uploads, vendor-specific structured forms, menu reordering/catering calculations, day-by-day scheduling, calendar export, RSVP, notification delivery/quiet hours/snooze, installable PWA, video export, private sign-in and cross-device sync still need implementation or external connections. The reminder and assistant panels explicitly show their disconnected state. Phone access outside this machine requires approved hosting; no public deployment has been made. Confirm phone platform before installation instructions.

Event year 2026 and INR are provisional. Countdown appears only after explicit confirmation and timezone selection. Supported event timezones are India, New York and UTC. Appointment input currently requires explicitly written timezone information; it does not schedule notifications.

## Artwork

`public/couple.webp` is original generated miniature diorama art. Small section illustrations are original SVG components. Fani's ivory outfit is provisional. Characters are stylized, not based on reference photos. Respect reduced-motion preferences. Fonts have local serif/sans fallback if Google Fonts is unavailable.

Source is in the existing sriya19/Pelli-Panchaythi checkout. This work has not been pushed and repository visibility has not been changed or verified.

## GitHub Pages

The Vite base path is configured for `/Pelli-Panchaythi/`. The included `.github/workflows/pages.yml` tests, builds and deploys pushes to `main`. Repository Settings → Pages → Build and deployment → Source must be set to **GitHub Actions**. Once deployed, the expected address is `https://sriya19.github.io/Pelli-Panchaythi/`. Do not assume the site is live until a successful Pages deployment.

The website is a static app. Browser-local updates, payment records and contacts are not uploaded to GitHub. The starter names, ceremony details and initial outfit costs are bundled in the website and visible to anyone able to access it. This is not an authenticated private planner.
