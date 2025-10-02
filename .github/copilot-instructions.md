# Copilot Instructions for Church So Blessed International Website

## Project Overview
This is the official website repository for Church So Blessed International, hosted on GitHub Pages.

## Code Style and Standards

### General Guidelines
- Write clean, semantic HTML5 code
- Use modern CSS3 features and responsive design principles
- Follow web accessibility standards (WCAG 2.1 Level AA)
- Ensure mobile-first responsive design
- Optimize for performance and fast load times

### HTML
- Use semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- Include proper meta tags for SEO and social media sharing
- Ensure all images have descriptive `alt` attributes
- Use proper heading hierarchy (h1-h6)

### CSS
- Prefer CSS custom properties (variables) for theming
- Use flexbox and CSS Grid for layouts
- Follow mobile-first approach with min-width media queries
- Keep selectors specific but not overly complex
- Organize styles logically (base, layout, components, utilities)

### JavaScript
- Use modern ES6+ syntax
- Prefer vanilla JavaScript or lightweight libraries
- Ensure progressive enhancement (site works without JS)
- Minimize dependencies to keep the site fast
- Add comments for complex logic

### Accessibility
- Ensure keyboard navigation works throughout the site
- Provide ARIA labels where appropriate
- Maintain sufficient color contrast ratios
- Test with screen readers when adding interactive elements
- Include skip-to-content links

## Content Guidelines

### Church-Related Content
- Maintain a welcoming, inclusive, and positive tone
- Respect religious sensitivity and diversity
- Keep content family-friendly
- Use clear, simple language accessible to all audiences
- Include proper attribution for quotes or borrowed content

### Images and Media
- Optimize all images before committing (use WebP format when possible)
- Keep file sizes reasonable (< 500KB for images)
- Include descriptive filenames
- Provide captions or context for images

## File Organization
- Keep the root directory clean
- Use logical folder structure (e.g., `/assets`, `/css`, `/js`, `/images`)
- Name files using lowercase with hyphens (kebab-case)

## GitHub Pages Specific
- Test locally before pushing to production
- Be mindful that changes go live immediately
- Respect the `_config.yml` if using Jekyll
- Keep the repository size reasonable (GitHub Pages has 1GB limit)

## Security and Privacy
- Do not commit sensitive information (API keys, passwords, etc.)
- Respect user privacy in any forms or data collection
- Use HTTPS for all external resources
- Validate and sanitize any user inputs

## Performance
- Minimize HTTP requests
- Use lazy loading for images below the fold
- Minify CSS and JavaScript for production
- Enable browser caching where possible
- Test on various devices and connection speeds

## Testing
- Test across multiple browsers (Chrome, Firefox, Safari, Edge)
- Verify responsive behavior on various screen sizes
- Check accessibility with automated tools
- Validate HTML and CSS
- Test all links and navigation

## Documentation
- Update README.md with any significant changes
- Comment complex code sections
- Document any build processes or dependencies
- Keep instructions clear for future maintainers
