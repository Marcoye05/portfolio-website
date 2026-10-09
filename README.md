# portfolio-website

# Marco Ye's Portfolio Website

A personal portfolio site built with HTML5 and CSS3 for INFR3120 - Web and Scripting Programming.

## Live Site
https://github.com/Marcoye05/portfolio-website

## Pages
- Home (index.html)
- About Me (about.html)
- Projects (projects.html)
- Contact Me (contact.html)

## Responsive Design - Fluid Design & Media Queries

This site uses three separate CSS files, linked via media queries in each
page's <head>, with NO Flexbox used anywhere (as required):

| Viewport | File | Breakpoint | Why |
|---|---|---|---|
| Laptop/Desktop | style.css | min-width: 961px | Full layout with larger spacing, suitable for wide monitor screens |
| Tablet | tablet.css | min-width: 481px and max-width: 960px | Slightly tighter spacing and fluid widths to fit mid-size screens like iPads |
| Mobile | phone.css | max-width: 480px | Larger font size (18px) for readability, full-width stacked nav buttons for easy tapping, higher-contrast flat header color for outdoor/sunlight visibility |

All widths use percentages (e.g. #wrapper { width: 90%; }) rather than fixed
pixel values, satisfying the fluid design requirement.

## Gradients

- **Linear gradient (straight)**: used on the `<header>` background on all
  4 pages - `linear-gradient(to right, #1B3A5C, #2A9D8F)` (navy to teal)
- **Angled linear gradient**: used on:
  - `<section>` hover state in projects.html - `linear-gradient(45deg, ...)`
  - Submit/reset buttons in contact.html - `linear-gradient(135deg, #E76F51, #E9C46A)`

## Color Scheme

Created using Adobe Color (https://color.adobe.com/create).

Hex values: #1B3A5C (navy), #2A9D8F (teal), #E76F51 (coral), #E9C46A (gold), #F7F3E9 (cream)

[Describe here whether it's complementary/harmonious and why you picked it -
e.g. "I chose a harmonious blue-teal base with a warm coral/gold accent pair
to keep the site feeling calm and professional while still having visual
contrast for buttons and links."]

[Optional: paste a screenshot of your Adobe Color scheme here]

## External Code / Citations

[If you used ANY code from outside the lecture materials, list it here:
source URL, author, and what it's used for. Example:
"Form validation pattern attribute referenced from MDN Web Docs
(developer.mozilla.org) - used in contact.html for phone number validation."

If everything is from the lecture notes/slides, state that instead:
"All code is based on lecture materials and examples provided in class
(Weeks 1-4). No external code sources were used beyond course content."]

## Testing & Validation

- [ ] HTML validated with W3C Markup Validator - 0 errors
- [ ] CSS validated with W3C CSS Validator - 0 errors
- [ ] All links