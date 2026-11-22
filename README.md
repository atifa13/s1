hellooooo


# Student Portfolio Website

A clean, responsive personal portfolio website for students — built with plain HTML and CSS, no frameworks needed.

---

## 📁 Files

| File | Purpose |
|---|---|
| `index.html` | All webpage content and structure |
| `style.css` | Styling, layout, colours, and responsiveness |
| `README.md` | This file — project description |

---

## 🌐 Sections

- **Hero** — Name, role, and call-to-action button
- **About Me** — Short bio and key info cards
- **Skills** — Languages, frameworks, and tools grouped by category
- **Projects** — Cards showing three sample projects
- **Contact** — Email, GitHub, LinkedIn, and phone links

---

## ✏️ How to Personalise

Open `index.html` and update:

1. **Your name** — replace `Alex Johnson` and the initials `AJ`
2. **About text** — rewrite the two paragraphs in the `#about` section
3. **Info cards** — update degree, location, graduation year, and what you're looking for
4. **Skills** — add or remove `<span class="tag">` items in each skill group
5. **Projects** — edit the three project cards (title, description, tags, emoji)
6. **Contact links** — replace `href` values with your real email, GitHub, and LinkedIn URLs

For colours and fonts, edit the `:root` variables at the top of `style.css`.

---

## 🚀 Running the Project

No build step needed. Just open `index.html` in any web browser:

```bash
# Option 1 — double-click index.html in your file manager

# Option 2 — from the terminal
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

---

## 🌱 Git Practice Ideas

This project is great for practising Git because every small change is meaningful:

| Change to make | Git concepts practised |
|---|---|
| Update your name and bio | `git add`, `git commit` |
| Add a new project card | Branching, merging |
| Change the colour theme in `style.css` | Viewing diffs with `git diff` |
| Add a new Skills group | Staging selected changes |
| Revert a colour change you don't like | `git revert` or `git checkout` |

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, grid)
- No JavaScript libraries
- No build tools — open and edit directly
