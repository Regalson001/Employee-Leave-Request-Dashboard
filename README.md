# LeaveFlow — Employee Leave Request Dashboard

<div align="center">

### BETTER VISIBILITY. BETTER TIME-OFF PLANNING.

A modern, responsive employee leave management dashboard concept built with semantic HTML5 and CSS3.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Responsive-Design-0D9B8A?style=for-the-badge)](#-responsive-design)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-172B4D?style=for-the-badge&logo=github)](#-live-demo)

**A clean HR dashboard interface designed for clarity, usability, and professional presentation.**

</div>

---

## Overview

**LeaveFlow** is a front-end portfolio project that presents an employee leave request dashboard through a modern business interface.

The dashboard brings together illustrative leave balances, request statuses, a request history table, and an employee leave application form. Its design focuses on clear information hierarchy, consistent styling, and a responsive experience across desktop, tablet, and mobile screens.

This project demonstrates how common business interface elements can be structured and styled using HTML and CSS without relying on a front-end framework.

> **Project type:** Front-end portfolio demonstration  
> **Primary technologies:** HTML5 and CSS3  
> **Interface:** Employee leave management dashboard  
> **Data:** Static demonstration content

## Key Features

- **Dashboard navigation** — A structured sidebar with links to the main dashboard sections.
- **Welcome header** — A clear introduction to the employee workspace.
- **Leave balance cards** — Illustrative annual, sick, and personal leave balances.
- **Pending request summary** — A visual overview of requests awaiting review.
- **Request history table** — Example leave applications with dates, durations, and status indicators.
- **Status badges** — Distinct visual treatments for Approved, Pending, and Rejected requests.
- **Leave application form** — Employee information, department, leave type, date range, manager, and reason fields.
- **Responsive layout** — CSS Grid, Flexbox, and media queries for different screen sizes.
- **Accessible form structure** — Explicit labels, appropriate input types, required fields, and native HTML validation.
- **Consistent design system** — Reusable CSS custom properties, colors, spacing, borders, and typography.
- **Reduced-motion support** — Respects users' reduced-motion preferences.
- **No build tools required** — Runs directly in a modern web browser.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure, forms, tables, and page content |
| CSS3 | Visual styling, layout, and responsive behavior |
| CSS Grid | Dashboard cards and form layout |
| Flexbox | Navigation, buttons, and aligned content |
| Media Queries | Responsive design across screen sizes |
| CSS Custom Properties | Reusable design tokens and consistent colors |
| Git & GitHub | Version control and source code hosting |
| GitHub Pages | Optional static website deployment |

The project does not require React, Bootstrap, Tailwind CSS, a database, or a build process.

## Design Highlights

**Visual direction:** Professional, minimal, organized, and business-focused.

- Deep navy navigation for a clear workspace structure.
- Teal accents for primary actions and active interface elements.
- White content cards against a subtle, cool-toned background.
- Color-coded request statuses for quick visual recognition.
- Clear typography and spacing to improve readability.
- Horizontally scrollable request table on narrower screens.

The interface is designed to resemble an internal HR application while remaining easy to explore as a portfolio project.

## Project Structure

```text
Employee-Leave-Request-Dashboard/
├── index.html
├── style.css
└── README.md
```

- `index.html` — Contains the dashboard structure, sample records, navigation, and leave application form.
- `style.css` — Contains the visual design, responsive breakpoints, status badges, and accessibility-related styling.
- `README.md` — Documents the project's purpose, features, setup, and limitations.

## Getting Started

### Prerequisites

You need:

- A modern web browser.
- Visual Studio Code or another code editor.
- Git, if you want to clone and publish the project.

### 1. Clone the repository

```bash
git clone https://github.com/Regalson001/Employee-Leave-Request-Dashboard.git
```

### 2. Open the project folder

```bash
cd Employee-Leave-Request-Dashboard
```

If the VS Code command-line launcher is available, open the folder with:

```bash
code .
```

Alternatively, open the folder using **File → Open Folder** in Visual Studio Code.

### 3. Run the dashboard

Open `index.html` in your browser, or use the Live Server extension in VS Code to preview the project locally.

No package installation or compilation is required.

## Responsive Design

The dashboard uses CSS Grid, Flexbox, and media queries to adapt its layout.

- **Desktop:** Fixed sidebar, multi-column summary cards, and a full dashboard workspace.
- **Tablet:** Adjusted navigation and card spacing.
- **Mobile:** Compact navigation, stacked summary cards, and a horizontally scrollable request table.

Responsive behavior should be verified using browser developer tools and, where possible, a real mobile device.

## Form and Data Limitations

This project is a **static front-end demonstration**, not a production HR management system.

- Leave balances are hard-coded examples and do not update automatically.
- Request counts and table records are illustrative.
- The form uses native browser validation but does not submit data to an HR system.
- There is no database, authentication, approval workflow, or persistent storage.
- The dashboard does not calculate working days, holidays, or leave entitlements.
- Sample employee information and request records should not be treated as real personnel data.

A production implementation would require a secure backend, identity and access controls, validated business rules, persistent storage, and appropriate employee-data privacy safeguards.

## Testing Checklist

- [ ] Dashboard navigation links move to their intended sections.
- [ ] Summary cards display correctly at different widths.
- [ ] The request table remains usable on small screens.
- [ ] Required form fields and email validation work.
- [ ] The reset button clears the form fields.
- [ ] Keyboard users can navigate links, controls, and form fields.
- [ ] Focus indicators remain visible.
- [ ] Text remains readable on different screen sizes.
- [ ] No unexpected horizontal page overflow appears.
- [ ] The GitHub Pages deployment loads successfully, if enabled.

## Future Enhancements

Possible next steps include:

1. Add JavaScript to calculate requested leave duration and improve form interactions.
2. Implement dynamic balances and request status updates.
3. Connect the form to a backend and database.
4. Introduce employee authentication and role-based permissions.
5. Build manager approval and rejection workflows.
6. Add leave-policy configuration, weekends, and public holiday calculations.
7. Add automated accessibility and responsive-layout tests.

These enhancements would extend the project from a static interface into a more complete leave management application.

## Live Demo

After enabling GitHub Pages, the project should be available at:

`https://regalson001.github.io/Employee-Leave-Request-Dashboard/`

To publish it, open the repository's **Settings → Pages**, select **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, and save.

Allow the deployment to finish before sharing the link.

## Author

**Stephen Oyugi**  
*Front-End Developer | HTML5 | CSS3*

This project is part of my front-end development portfolio, demonstrating my ability to build structured, responsive, and visually polished business interfaces.

- **GitHub profile:** [@Regalson001](https://github.com/Regalson001)
- **Project repository:** [Employee-Leave-Request-Dashboard](https://github.com/Regalson001/Employee-Leave-Request-Dashboard)

## License

This project is intended for learning and portfolio demonstration. No license is specified by default. If you want others to reuse the code under an open-source license, add a `LICENSE` file with the terms you choose.

---

<div align="center">

**LEAVEFLOW · EMPLOYEE LEAVE DASHBOARD**

Built with care by Stephen Oyugi.

</div>
