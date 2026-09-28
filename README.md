# Habit Ring

Responsive 30-day circular habit tracker for phone and laptop.

## Features
- Nine editable habits
- Daily completion screen
- Circular monthly tracker
- Monthly dashboard
- Previous/next month selection
- Local backup/import
- Installable PWA support
- Responsive mobile/desktop layout

## Data storage
The current GitHub Pages build stores data in the browser with `localStorage`.

That means:
- tracking works immediately on a device;
- no fake or insecure password is used;
- phone and laptop do **not** automatically synchronize yet.

For true account login and cross-device sync, the next version should connect a backend such as Supabase.

## GitHub Pages
In the repository, open **Settings → Pages** and choose **Deploy from a branch**.
Use:
- Branch: `main`
- Folder: `/ (root)`

The site URL will be:

https://saitejajarabala.github.io/habit-ring/
