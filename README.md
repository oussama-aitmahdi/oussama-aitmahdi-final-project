# Hemayati – Rights & Protection

**Hemayati** is a multi-page website that helps people in Morocco understand their legal rights, recognize harassment and violence, protect themselves, and find the right support. It was built for the **16 Days of Activism against Gender-Based Violence (25 November – 10 December)** and uses clear, simple language.

## Pages

| Page | File | What it does |
|------|------|--------------|
| Home | `index.html` | Hero section, the platform's mission, four pillars (know your rights, recognize violence, protect yourself, find support), a section on **26 November 2020** (CESE declaring violence against women a national emergency) and links to the other pages. |
| Help | `public/pages/help.html` | "You are not alone." Choose a situation (street harassment, domestic violence, online harassment, workplace harassment, physical and verbal abuse, sexual harassment, stalking and intimidation) and follow a six-step guide. It also has everyday safety tips and a private help-request form. |
| Laws | `public/pages/laws.html` | Moroccan laws explained simply: Law 103-13, the penal code, workplace law, child protection and cybercrime. It lists your rights, what is prohibited, what to do if your rights are violated, and where to get legal help. |

### The six-step guide on the Help page
1. Understand the situation
2. Immediate actions
3. Safety precautions
4. Evidence preservation
5. Who to contact
6. Possible legal options

### Help request form
Fields: type of problem, description, whether it is ongoing, whether you feel safe, type of help needed (legal, medical, psychological, police, information only), and optional name and contact. The form is front-end only for now and is not connected to a backend.

## Tech stack
- **HTML5**
- **[Tailwind CSS v4](https://tailwindcss.com/)** – via the CDN browser build on the pages, with `@tailwindcss/cli` available for compiling `public/css/input.css` to `output.css`
- **[Flowbite](https://flowbite.com/)** 4.0.1 – navbar and interactive components
- **Custom CSS** – the "date" section and gradient banner
- **Google Fonts** – Bodoni Moda, used for titles

## Project structure
```
finale/
├── index.html              # Home page
├── package.json            # Tailwind dependencies
├── public/
│   ├── css/
│   │   ├── input.css       # Tailwind entry + custom styles
│   │   └── output.css      # Compiled CSS
│   ├── images/             # SVG illustrations and background image
│   ├── pages/
│   │   ├── help.html
│   │   └── laws.html
│   └── videos/
└── README.md
```

## Getting started

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd finale
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. (Optional) Rebuild the CSS after editing `input.css`:
   ```bash
   npx @tailwindcss/cli -i ./public/css/input.css -o ./public/css/output.css --watch
   ```
4. Open `index.html` in your browser, or serve the folder with a local server such as VS Code Live Server.

## Emergency numbers (Morocco)
**19 / 15 / 177**: police, ambulance and gendarmerie.

## Contact
- Email: hemayati@gmail.com
- Phone: 05 68 75 46 09
- Availability: 24/7

## Privacy
The site does not store any personal data.

## License
© 2026 Hemayati. All rights reserved.