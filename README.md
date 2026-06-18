# Personal Portfolio Website

A clean, modern, multi-page personal portfolio website built entirely with HTML5 and CSS. This project is meticulously crafted to adhere to semantic HTML standards, WCAG 2.1 accessibility guidelines, and SEO best practices, aiming for a perfect 100 score in Google Lighthouse audits.

## Live Demo
[https://vedant-211.github.io/HTML5-Semantic-Structure-Accessibility/](https://vedant-211.github.io/HTML5-Semantic-Structure-Accessibility/)

## File Structure

```
/
├── index.html       # Home page (Hero, Intro, Featured Projects)
├── about.html       # About page (Bio, Education, Skills)
├── projects.html    # Projects page (Grid of project cards)
├── contact.html     # Contact page (Accessible contact form)
├── css/
│   └── style.css    # Global stylesheet, CSS variables, and layout
└── README.md        # Project documentation
```

## Features

### 🌟 Accessibility (A11y)
The website is built with strict adherence to WCAG 2.1 standards:
- **Semantic HTML**: Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` to provide meaningful document structure.
- **Heading Hierarchy**: Logical progression of `<h1>` to `<h6>` tags without skipping levels.
- **Skip-to-Content Link**: A visually hidden link that becomes visible on keyboard focus, allowing screen reader and keyboard users to bypass navigation.
- **Keyboard Navigation**: All interactive elements are fully reachable and usable via the `Tab` key.
- **Visible Focus States**: Custom `:focus-visible` outlines are implemented across all interactive elements (`a`, `input`, `textarea`, `button`) for clear visual feedback.
- **ARIA Attributes**: Strategic use of `aria-label`, `aria-labelledby`, `aria-hidden`, and `aria-current` to provide additional context to assistive technologies where native HTML falls short.
- **Accessible Forms**: Explicitly associated `<label>` elements with input fields using the `for` and `id` attributes. `required` and `aria-required="true"` ensure users know what fields are mandatory.
- **Color Contrast**: A carefully selected color palette guarantees text meets or exceeds the required 4.5:1 contrast ratio against backgrounds.

### 🔍 Search Engine Optimization (SEO)
- **Meta Tags**: Unique and descriptive `<title>`, `<meta name="description">`, and `<meta name="keywords">` for every individual page.
- **Canonical URLs**: `<link rel="canonical">` implemented on all pages to prevent duplicate content issues in search indexing.
- **Open Graph Protocol**: `og:title`, `og:description`, `og:type`, and `og:url` tags are included to ensure content looks great when shared on social media platforms.
- **Semantic Structure**: Search engine crawlers can easily parse the page content and structure due to strict semantic HTML5 conventions.

### 📱 Responsive Design
- **Mobile-First Approach**: CSS is written starting with the smallest screen sizes, scaling up for larger devices using `min-width` media queries.
- **CSS Grid & Flexbox**: Modern layout techniques ensure content flows beautifully on phones, tablets, and desktop displays.
- **Fluid Typography**: Responsive headings that scale appropriately.

## Setup & Deployment

Since this project contains only static HTML and CSS files, no complex build process or package manager is required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vedant-211/HTML5-Semantic-Structure-Accessibility.git
   ```
2. **Local Development:**
   Simply open any `.html` file directly in your web browser, or use a tool like VS Code Live Server for hot-reloading.
3. **Deployment:**
   The repository is fully ready to be deployed to GitHub Pages. Push the code to the `main` branch and enable GitHub Pages from the repository settings, pointing it to the root `/` directory.

## Author
[John Doe](https://github.com/vedant-211)
