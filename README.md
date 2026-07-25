# Dashborad-Template<img width="1880" height="850" alt="Screenshot 2026-07-25 171509" src="https://github.com/user-attachments/assets/b9d07894-a4d8-4cdc-82e3-7bd1a0f2221b" />

A responsive HTML/CSS dashboard template — a fully functional UI kit with multiple pages for personal dashboard management. It's designed for developers to use as a starter template for building dashboard interfaces with features like project tracking, user profiles, settings, and activity monitoring.

### Stack
- **Language(s):** HTML5, CSS3, JavaScript
- **Framework / runtime:** Vanilla HTML/CSS (no framework dependencies)
- **Notable libraries:** Font Awesome (icon library), Google Fonts (Open Sans), custom CSS framework

## How it's organized

```
css/
  all.min.css      Font Awesome icons (minified)
  framework.css    Utility-first CSS classes (spacing, colors, layout)
  master.css       Component styles and page-specific layouts

imgs/               Asset directory (avatars, icons, illustrations)
webfonts/           Font files for Font Awesome

index.html          Main dashboard page with widgets
profile.html        User profile overview with skills/activities
settings.html       Dashboard configuration and preferences
projects.html       Project management and display
courses.html        Course listing page
friends.html        Contact/friends page
files.html          File management interface
plans.html          Subscription/pricing plans page
```

**How it fits together:** The template uses a fixed sidebar navigation (8 pages linked via href) with a responsive two-column layout. Each page loads the same CSS framework and master styles, maintaining consistent branding (color scheme, typography, spacing). The dashboard home (`index.html`) displays 15+ widget components—welcome card, quick draft, targets, tickets, news, tasks, uploads, project progress, reminders, social stats, and a projects table. Responsive breakpoints at 767px collapse the sidebar to icons and adjust grid layouts for mobile.

## How to run it

Simply open any `.html` file in a web browser. No build process or server required—it's a static site:

```bash
# Option 1: Open in browser directly
open index.html

# Option 2: Use a local web server (Python)
python -m http.server 8000

# Option 3: Use a local web server (Node.js)
npx http-server
```

Then navigate to `http://localhost:8000` and click through the sidebar navigation to explore all pages.

## 👤 Author

**Osman Adam**
- GitHub: [@osmanadam-dev](https://github.com/osmanadam-dev)
- Portfolio: [lnk.bio/osmanadam-dev](https://lnk.bio/osmanadam-dev)
