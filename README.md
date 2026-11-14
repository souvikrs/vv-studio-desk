# Studio Desk (VV Automate) — demo

Front-end-only demo of an AI front office and back office for wedding, event and film studios.
Sister product to Contractor Desk (`../vv-contractor-desk`). Everything shown is sample data;
no backend, no AI calls.

- Open `index.html` in a browser. No build step.
- `index.html#v=<view>` opens a dashboard view directly. Views: `home`, `wa`, `calls`,
  `bookings`, `payments`, `delivery`, `brain`, `usage`, `edit`.
- Plan prices on the landing page are hidden on the hosted page ("Ask for a quote") because they are not final. They live in the `PLANS`
  constant near the top of the script; set `SHOW_PRICES=true` to show them.
- The sample studio is "Shubho Drishti Studio" (invented; the `STUDIO` constant).
- Built 15 Nov 2026.
- Hosted with GitHub Pages from the public repo souvikrs/vv-studio-desk: https://souvikghoshrs.com/vv-studio-desk/

The product plan and pricing notes are kept locally and are not in this repository.
