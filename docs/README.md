# Internal Documentation – Suudi Portfolio

This documentation provides internal technical details for my portfolio , covering the project structure, architecture, design principles, and ongoing development roadmap.

>  This file is meant for maintainers, collaborators, or future versions of the portfolio.  
> The public-facing overview is in the root `README.md`.

## Design Philosophy

- **Mobile-First Approach**: All layouts are optimized starting from small screens upward.
- **BEM Naming Convention**: Follows `block__element--modifier` pattern for CSS class names.
- **CSS Variables**: Defined in `:root` for easy theme customization and reusability.
- **Grid and Flex Layouts**: Used for project cards, header sections, and responsiveness.

## CSS Architecture
- **Global Variables**: Colors, font sizes, spacing, and breakpoints defined in `:root`.
- **Utilities**: Classes for spacing, flex, grid, etc.
- **Layout Classes**: Header, main, sections, footer with clearly separated roles.
- **Media Queries**: Mobile-first breakpoints for responsive scaling.

## CSS-Only Filter Logic

The project and blog filters use **CSS-only logic**:

- Uses anchor links with IDs
- Filters based on `:target` pseudo-class
- No JavaScript involved

## Roadmap

| Feature             | Status  | Priority | Notes                          |
| ------------------- | ------- | -------- | ------------------------------ |
| Dark mode           | Planned | High     | Toggle CSS variables via class |
| PWA integration     | Planned | Medium   | Enable offline mode            |
| Keyboard navigation | Planned | Medium   | Improve accessibility          |
| JSON project system | Backlog | Low      | Enable future JS integration   |

## Suggested Improvements

* Modularize CSS by feature (e.g., `/styles/components/`)
* Split content sections into includes (for templating in future static site generator)
* Implement `aria-live` for better form feedback
* Add CI (lint check or HTML/CSS validator in GitHub Actions)

## Contact Maintainer
If you're reviewing or maintaining this project in the future:
*  Email: **[abdisalansucdi@gmail.com](mailto:abdisalansucdi@gmail.com)**
*  LinkedIn: [Sucdi Abdisalan](https://www.linkedin.com/in/sucdi-abdisalan-0a2349267/)
*  Main repo: [github.com/Suudi-sudo/portfolio](https://github.com/Suudi-sudo/portfolio)


