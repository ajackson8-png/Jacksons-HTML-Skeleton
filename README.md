# Jacksons-HTML-Skeleton

# Milestone 2: Accessibility and Visual Design

## 1. Accessibility Fixes

I made several changes to improve the accessibility of my website and make it easier for people to use.

- I added a skip link to all three pages so keyboard users can jump directly to the main content.
- I added the correct language attribute (`lang="en"`) to all three HTML pages so screen readers can identify the language.
- I added labels to the navigation sections to help users understand the purpose of each navigation area.
- I added visible keyboard focus outlines so users can see which link or element they are selecting.
- I used `aria-current="page"` to identify the current page in the navigation.
- I added a `main` element and an ID to each page so the skip link has a clear destination.
- I added proper labels to the contact form fields so users know what information to enter.
- I added a fieldset and legend to group the contact reason options.
- I added error messages and accessible error states to help users correct mistakes when filling out the contact form.
- I added form validation to check that required information is entered correctly.
- I included reduced-motion styling to help users who prefer less animation.

## 2. Gestalt Principles

I used two Gestalt principles to make my website look organized and consistent.

- **Proximity:** I grouped related information and project cards together using CSS Grid and consistent spacing. This helps visitors understand which information belongs together.
- **Similarity:** I used the same purple color palette, fonts, borders, and navigation style across all three pages. This makes the website look consistent and helps visitors recognize the same design throughout the portfolio.

## 3. Color Palette

I used a dark purple and galaxy-inspired color palette throughout my website.

- Background: `#020006`
- Dark Purple: `#140020`
- Purple: `#68249f`
- Bright Purple: `#a64de0`
- Lavender: `#e6b3ff`
- Main Text: `#f5edff`
- Active Navigation: `#7020a8`

## 4. Accessibility Testing

I tested all three pages using the WAVE Web Accessibility Evaluation Tool.

I also used the WAVE Contrast Checker to check my text and background color combinations. I originally tried using the WebAIM Contrast Checker, but I was unable to access it because it required permission.

The WAVE results showed zero errors and zero contrast errors on all three pages.

### Final WAVE Results

| Page | Errors | Contrast Errors | Alerts | AIM Score |
|---|---:|---:|---:|---:|
| Home | 0 | 0 | 1 | 10/10 |
| Projects | 0 | 0 | 0 | 10/10 |
| About | 0 | 0 | 0 | 10/10 |

The Home page had one redundant link alert. The Projects and About pages had zero alerts. All three pages received an AIM score of 10 out of 10.

## 5. Final Reflection

Overall, I improved my website by making it more accessible, organized, and consistent. I learned how to use accessibility features in HTML, improve keyboard navigation, organize content using CSS Grid, and use Gestalt principles in my design.

I also learned how important it is to test a website with accessibility tools instead of only focusing on how it looks. These changes helped me improve my portfolio and my understanding of accessible web design.