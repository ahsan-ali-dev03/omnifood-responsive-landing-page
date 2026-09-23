# OmniFood – Responsive Food Delivery Landing Page

## Project overview

OmniFood is a responsive, single-page food delivery landing page built for the Responsive Food Delivery Landing Page (OmniFood Demo) assignment. The page recreates the required visual structure with a hero banner, how-it-works section, city cards, testimonials, pricing plans and footer.

## Technologies used

- HTML5
- CSS3
- CSS Grid and Flexbox
- Responsive media queries
- No backend
- No JavaScript required

## Project structure

```text
omnifood-responsive-landing-page/
├── index.html
├── style.css
├── README.md
└── assets/
    ├── hero.jpg
    ├── food.jpg
    ├── logo.jpg
    ├── lisbon.svg
    ├── london.svg
    ├── berlin.svg
    ├── san-francisco.svg
    ├── avatar-alberto.svg
    ├── avatar-joana.svg
    └── avatar-milton.svg
```

## How to run

No installation or server is required.

1. Download or clone the project.
2. Open `index.html` directly in a web browser.

## Responsive breakpoints used

- **Desktop:** 1200px and above — full grid layout.
- **Tablet:** 834px and below — sections stack where needed and grids use two columns.
- **Mobile:** 390px and below — single-column layout and CSS-only hamburger navigation.

The CSS also includes an intermediate breakpoint so the page remains usable between the required device widths.

## Mandatory sections implemented

1. Header + Hero
2. How It Works (3 steps)
3. Our Cities (4 cards)
4. Testimonials (3 quotes)
5. Pricing Plans (3 cards)
6. Footer

## Responsive requirements handled

- No horizontal scrolling
- Images resize within their containers
- Text and buttons remain readable
- Desktop grids become two columns on tablet where appropriate
- Mobile grids become single-column
- Navigation changes to a hamburger menu on small screens

## Assignment restrictions

The project uses HTML and CSS only. No backend or form processing is included. JavaScript is not required for the navigation because the mobile menu uses a CSS checkbox toggle.
