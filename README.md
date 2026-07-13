# TaskFlow Kanban - Simple HTML/JS Version

A fully functional Kanban board in a **single HTML file** — no build tools, no npm, no dependencies to install. Just open the file in a browser or upload to GitHub Pages.

## Features

- Drag & Drop between columns (native HTML5 API)
- Create, edit, delete tasks with modals
- Priority levels (Low, Medium, High) with color badges
- Categories (Design, Development, Testing, etc.)
- Color labels for visual organization
- Due dates with overdue detection
- Search, filter by priority/category/status
- Sort by date, priority, or creation date
- Statistics dashboard (5 animated cards)
- Dark/Light mode toggle
- Data persistence via LocalStorage
- Export/Import JSON
- Toast notifications
- Fully responsive (mobile, tablet, desktop)
- Glassmorphism UI design

## How to Use

### Option 1: Open Locally
Simply double-click `index.html` — it works right away.

### Option 2: GitHub Pages (Free Hosting)

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to **Settings → Pages**
4. Set **Source** to **Deploy from a branch**
5. Select **main** branch and **/(root)** folder
6. Click **Save**
7. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`

### Option 3: Netlify / Vercel (Drag & Drop)
1. Go to [netlify.com](https://netlify.com) or [vercel.com](https://vercel.com)
2. Drag and drop the `index.html` file
3. Your site is live instantly

## File Structure

```
taskflow-kanban-simple/
└── index.html    (everything in one file!)
```

That's it. No `node_modules`, no build step, no bundler.

## External Resources Used (CDN)

- **Tailwind CSS** (via CDN) — styling
- **Font Awesome** — icons
- **Google Fonts (Inter)** — typography

All loaded automatically when you open the file.

## Data Storage

All tasks are saved to your browser's **LocalStorage**, so they persist between sessions. You can also export your data as JSON and import it later.

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

MIT — free to use, modify, and distribute.
