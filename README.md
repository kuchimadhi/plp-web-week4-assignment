# SpendWise Dashboard Shell

This project is a static dashboard mockup built for the PLP Week 4 assignment. The goal was to recreate a modern financial dashboard using CSS Grid and Flexbox while keeping the layout responsive and visually polished.

## What is built

- A sidebar navigation panel for the app menu
- A top header area with overview text and action buttons
- A summary section with three key financial cards
- Six budget/category cards showing realistic spending data
- A responsive layout that collapses to one column on screens below 768px
- Subtle card hover and focus animations for better interaction feedback
- A dark-mode variant using `prefers-color-scheme: dark`

## Layout structure

- The overall page is arranged with CSS Grid in `index.html` and `style.css`
- Flexbox is used inside the sidebar navigation, top toolbar, and each content card
- The design uses CSS variables on `:root` to keep the theme consistent

## Files

- `index.html` — dashboard markup and content structure
- `style.css` — all styling, responsive behavior, and theme variables
- `README.md` — project summary and explanation

## Local preview

Open `index.html` in a browser or run a local static server, such as:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
