*Pacing Timer — Aggro Study Mode ⚔️📚*

A tiny, ruthless study timer that bullies your procrastination.

Per-page, adaptive timer: finish a page faster than the shown time → the average time for remaining pages increases (you earn slack).

Finish late → the average time for remaining pages decreases (you pay for it).

Big circular timer + clear “LATE” state + keyboard-first controls keep you in motion.

🎯 How it works (simple math)

T = total session time (minutes)

P = total pages

E = elapsed time so far

d = pages done

L = P - d = pages left

R = T - E = remaining time

New average per page:

A = R / L


Example: T = 60 min, P = 6 → initial A = 10 min/page.

If you finish page 1 in 6 min (early by 4): E = 6, R = 54, L = 5 → A = 10.8 min/page (you earned slack).

If you take 14 min (late by 4): E = 14, R = 46, L = 5 → A = 9.2 min/page (remaining time tightens).

🧭 Features

Single-file HTML/CSS/JS — open in any modern browser.

Adaptive reallocation: remaining time auto-rebalanced after every page.

Overtime tracking: counts late minutes and visually calls you out.

Keyboard flow: N = Next, Esc = Abort. Hands stay on the keys.

Lightweight UI, prominent circular timer for pure urgency.

⚙️ Quickstart

Open timer.html in your browser.

Enter Total pages and Total time (minutes).

Press Start Session.

Work the current page until the timer rings — then hit Next (or press N).

Finish all pages to see a sharp session summary.

🔧 Make it yours

Tweak the theme/colors at the top of the file — CSS variables make it easy:

:root{
  --bg: #0f1724;      /* background */
  --accent: #ff3b30;  /* primary urgency color */
  --ok: #10b981;      /* success / saved-time color */
  --danger: #ff2d55;  /* late color */
}


Want it crueler? Edit the allocation logic in the script to scale penalties or bonuses.
