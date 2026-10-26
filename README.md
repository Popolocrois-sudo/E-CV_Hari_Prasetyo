# Hari Prasetyo | Online Portfolio (e-CV)

An interactive, single-page online portfolio for **Hari Prasetyo**, an IT Helpdesk & Operation professional and Information Systems student. Built with plain HTML, CSS and JavaScript, with no build step or dependencies.

## Features

- Dark and light theme toggle (remembers your choice and respects system preference)
- Animated role text in the hero section
- Interactive work history: pick a role or step through it with Newer / Earlier buttons
- Expandable education timeline
- Awards, languages and interests
- One-click "Copy email" button
- Smooth scrolling, scroll reveal animations and active section highlight in the navigation
- Responsive layout for desktop, tablet and mobile

## Project Structure

```
.
├── index.html   # the whole site (HTML, CSS and JS in one file)
├── photo.jpg    # profile photo
└── README.md
```

## Run Locally

Open `index.html` in any browser. Keep `photo.jpg` in the same folder.

Or serve it locally:

```bash
npx serve .
```

## Deploy to Vercel

1. Push this repository to GitHub.
2. In [Vercel](https://vercel.com), choose **Add New → Project** and import the repository.
3. Set **Framework Preset** to **Other**, leave the build command empty, and click **Deploy**.

Every push to the main branch redeploys the site automatically.

## Customize

All content lives in `index.html`:

- **Text and sections:** edit the HTML inside `<main>`.
- **Work history:** edit the `jobs` array in the `<script>` block.
- **Colors:** change the CSS variables in `:root` (dark) and `:root[data-theme="light"]`.
- **Photo:** replace `photo.jpg` with another image of any size (a 4:5 portrait works best).

## Tech

HTML5 · CSS3 · Vanilla JavaScript · Google Fonts (Space Grotesk, JetBrains Mono)

## Contact

Email: shin.hariday@proton.me
