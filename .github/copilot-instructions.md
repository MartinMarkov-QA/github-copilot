# GitHub Copilot Instructions

## Project Overview
This project is a web application built with React and React Router, featuring ISTQB (International Software Testing Qualifications Board) branding and navigation.

## Code Style and Conventions

### JavaScript/React
- Use functional components with React Hooks
- Use camelCase for variable and function names
- Use PascalCase for component names
- Use arrow functions for event handlers
- Import React at the top of each component file

### File Organization
- Components: `/src/components/`
- Styles: Co-located with components (e.g., `Navigation.jsx` with `Navigation.css`)
- Each component should have its own CSS file

### Naming Conventions
- Component files: PascalCase (e.g., `Navigation.jsx`)
- CSS files: Match component name (e.g., `Navigation.css`)
- CSS classes: kebab-case (e.g., `nav-container`, `nav-links`)

## Documentation Standards

### File Headers
Add JSDoc comments at the top of each file:
```javascript
/**
 * @author [Author Name]
 * @role [Your Role]
 * @contact [Email/Contact Info]
 */
```

### Component Documentation
Document component props and purpose:
```javascript
/**
 * Navigation component providing site-wide navigation
 * @returns {JSX.Element} Navigation bar with logo and links
 */
```

## React Best Practices
- Use React Router's `Link` component for internal navigation (not `<a>` tags)
- Always include alt text for images for accessibility
- Use semantic HTML elements (`<nav>`, `<ul>`, `<li>`)
- Keep components focused and single-responsibility

## Dependencies
- react
- react-router-dom
- CSS for styling (no CSS-in-JS libraries)

## Accessibility
- Include descriptive alt text for all images
- Use semantic HTML structure
- Ensure proper heading hierarchy
- Test components with screen readers

## Version Control
- Write clear, descriptive commit messages
- Use feature branches for new work
- Keep commits atomic and focused