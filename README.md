# Hemayati – Rights & Protection

## 1. Project Overview

**Hemayati** is a website designed to help people in Morocco understand their legal rights, recognize harassment and gender-based violence, discover ways to protect themselves, and find appropriate support.

The project was created as part of the **16 Days of Activism Against Gender-Based Violence (25 November – 10 December)** initiative.

The website aims to provide accessible information, practical guidance, and resources in a clear and user-friendly way.

---

## 2. Technologies Used

The project was developed using the following technologies:

| Technology | Version | Purpose |
|---|---|---|
| HTML | HTML5 | Website structure and content |
| CSS | CSS3 | Custom styling and responsive design |
| Tailwind CSS | 4.3.5 | Utility-based styling |
| Tailwind CSS CLI | 4.3.5 | Generating the compiled CSS file |
| DaisyUI | 5.x | UI component styling |
| Google Fonts | Bodoni Moda | Typography for headings |

### Additional Tools
- **Flexbox:** Used to organize layouts and align elements.
- **CSS Media Queries:** Used to adapt layouts to smaller screens.
- **SVG:** Used for illustrations and icons.
- **CSS Transitions:** Used for hover effects and smooth interactions.
- **Custom CSS:** Used for specific sections and decorative elements.

---

## 3. Website Pages

### Page 1 – Home (`index.html`)

The home page introduces the purpose of Hemayati and presents its main services.

**Main elements:**
- Announcement banner displaying the 16 Days of Activism campaign dates.
- Navigation bar with links to Home, Help, and Laws.
- Hero section with the main message: "Your safety. Your dignity. Your rights."
- Illustration representing women's protection and safety.
- Introduction explaining why the platform exists.
- Information cards introducing the platform's main objectives.
- November 26 section highlighting the protection of women and girls.
- Section introducing the different pages of the platform.
- Footer containing navigation and contact information.

**Design:** A warm and welcoming design using cream backgrounds, brown headings, and orange accents.

### Page 2 – Help (`help.html`)

The Help page provides practical information and guidance for people experiencing harassment or violence.

**Main elements:**
- Introduction section: "You are not alone. Help is available."
- Different categories of situations:
  - Street harassment.
  - Domestic violence.
  - Online harassment.
- Practical safety tips.
- A personal guidance form allowing users to describe their situation.
- Dropdown selection for identifying the type of problem.
- Text areas for explaining what happened.
- Checkboxes for selecting relevant circumstances.
- Input fields for additional information.

**Design:** A calm and accessible interface using soft backgrounds, neutral input fields, and carefully selected accent colors.

### Page 3 – Laws (`laws.html`)

The Laws page introduces legal rights and explains the importance of legal protection.

**Main elements:**
- Introduction: "Know your rights. The law is on your side."
- Explanation of what is allowed and prohibited.
- Information about Moroccan laws protecting women and girls.
- Legal assistance and support information.
- Cards introducing different sources of legal help:
  - Lawyers and legal aid.
  - Women's rights associations.
  - Courts and public prosecutors.
- Call-to-action section directing visitors toward personal guidance.

**Design:** A professional and informative layout using dark brown headings, warm cream backgrounds, and orange highlights.

---

## 4. Color Palette

The website uses a warm color palette inspired by safety, trust, accessibility, and awareness.

### Main Colors

| Color | HEX Code | Usage |
|---|---|---|
| Dark Brown | `#713310` | Main headings, buttons, footer background |
| Orange Brown | `#B34A22` | Announcement banner, accents, decorative lines |
| Medium Brown | `#753916` | Navigation links |
| Orange | `#B7552E` | Links and secondary buttons |
| Light Cream | `#FDF4E9` | Main section backgrounds |
| Soft Peach | `#F9DAB8` | Icon backgrounds and decorative elements |
| Pale Beige | `#FBE9D4` | Highlighted sections and call-to-action backgrounds |
| Light Brown | `#EFCFAC` | Footer text |
| White | `#FFFFFF` | Cards, buttons, and text on dark backgrounds |
| Dark Grey | `#4A4A57` | Paragraphs and descriptive text |
| Grey | `#888892` | Secondary text |

### Page-Specific Colors

**Home Page**
- Hero background: `#FDF4E9`
- Main headings: `#713310`
- Announcement banner: `#B34A22`
- Main paragraphs: `#4A4A57`
- Icon backgrounds: `#F9DAB8`
- White content sections: `#FFFFFF`

**Help Page**
- Main headings: `#713310`
- Input backgrounds: `#F4F4F6`
- Input borders: `#E2E2E7`
- Highlight backgrounds: `#FDF4E9`
- Card backgrounds: `#FFFFFF`
- Accent colors: `#B34A22`, `#B7552E`
- Additional status and category colors: `#B63831`, `#CCA236`, `#886B25`, `#C79997`, `#FAEDEC`, and `#FEF9DE`.

**Laws Page**
- Main headings: `#713310`
- Section backgrounds: `#FDF4E9`
- Highlight backgrounds: `#FBE9D4`
- Icon backgrounds: `#F9DAB8`
- Links and buttons: `#B7552E`
- Footer background: `#713310`
- Footer text: `#EFCFAC`

---

## 5. Typography

The website uses **Bodoni Moda**, imported from Google Fonts.

- Main headings: Bodoni Moda, serif, bold.
- Section titles: Bodoni Moda, serif.
- Body text: Default sans-serif font.
- Navigation and buttons: Default sans-serif font.

Bodoni Moda was selected to give the website an elegant and professional visual identity.

---

## 6. Responsive Design

The website uses Tailwind CSS responsive utilities and CSS media queries.

Examples include:
- `max-sm:flex-col` to change horizontal layouts into vertical layouts on small screens.
- `max-sm:w-full` to make elements occupy the available width.
- Flexible containers using Flexbox.
- Responsive navigation layout.

The objective is to make the website usable on desktop, tablet, and mobile screens.

---

## 7. Project Structure

```text
finale/
│
├── index.html
├── README.md
├── package.json
├── package-lock.json
│
└── public/
    │
    ├── css/
    │   ├── input.css
    │   └── output.css
    │
    ├── images/
    │   ├── hero-women-shield.svg
    │   ├── card-home.svg
    │   ├── card-help.svg
    │   ├── card-laws.svg
    │   ├── card-finding-help.svg
    │   ├── finding-help-pin.svg
    │   ├── help-lantern.svg
    │   └── star.svg
    │
    └── pages/
        ├── help.html
        └── laws.html
```

---

## 8. Installation and Execution

To run the project locally:

1. Download or clone the project.
2. Open the project folder.
3. Install the dependencies:

```bash
npm install
```

4. Generate the CSS file using Tailwind CSS:

```bash
npx @tailwindcss/cli -i ./public/css/input.css -o ./public/css/output.css --watch
```

5. Open `index.html` in your browser.

**Note:** DaisyUI is included through a CDN in the HTML files.

---

## 9. Project Objective

The main objective of Hemayati is to make information about women's rights and protection more accessible in Morocco.

The website combines legal awareness, practical advice, and support resources in one place, encouraging people to understand their rights and seek appropriate assistance when needed.

---

**Project Name:** Hemayati – Rights & Protection  
**Theme:** Women's Rights and Protection Against Gender-Based Violence  
**Country:** Morocco  
**Campaign:** 16 Days of Activism Against Gender-Based Violence