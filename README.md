# Silm Academy Website

A complete, self-contained website for Silm Academy — one HTML file with everything built in (styling, scripts, images, and an admin panel).

## Files in this repo

- **index.html** — the entire website. This is the only file you need.

That's it. No separate CSS, JS, or image files — everything is bundled inside `index.html` so there's nothing else to upload or link up.

## How to host this on GitHub Pages

1. Create a new repository on GitHub (e.g. `silm-academy`).
2. Upload `index.html` to the root of the repo (drag-and-drop on github.com works fine, or use `git add` / `commit` / `push`).
3. Go to your repo's **Settings → Pages**.
4. Under "Source," choose **Deploy from a branch**, select the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will give you a live URL, usually:
   `https://yourusername.github.io/silm-academy/`
   It can take a minute or two to go live after the first deploy.

## Admin panel

- Click the lock icon (**Admin**) in the site header.
- Default password: `silm2026` — change this under **Settings** in the admin panel after logging in.
- From the admin panel you can edit: hero text, about section, courses (including photos), founder & advisor profiles, announcements, gallery, donation details, and contact info. You can also view admission applications and contact form messages.

## Important note on data storage

Content you edit in the admin panel (courses, announcements, gallery, admissions, messages, etc.) is saved using this artifact's built-in storage, tied to this specific file/session. If you host this exact file on GitHub Pages, admin edits made there will need a real backend to persist and sync across visitors — plain GitHub Pages only serves static files and has no database of its own.

If you want the admin panel to keep fully working (saving new courses, receiving real admission/contact submissions, etc.) after moving to GitHub Pages, let me know — I can help wire it up to a lightweight backend (e.g. Firebase, Supabase, or a small serverless API) that will work with static hosting.
