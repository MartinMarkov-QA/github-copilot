---
agent: Full-Stack Developer
description: "Create a new React component with proper testing and documentation"
---

Create a new React functional component following the project's best practices and conventions.

## Context

The component should be built using React hooks and follow the existing project structure. Include proper TypeScript types, accessibility features, and comprehensive documentation.

## Requirements

1. **Component Structure**
   - Use functional component with TypeScript
   - Implement proper prop types interface
   - Use React hooks (useState, useEffect, etc.) where appropriate
   - Follow existing naming conventions

2. **Styling**
   - Create a separate CSS file for component styles
   - Use semantic class names
   - Ensure responsive design
   - Follow BEM naming convention if applicable

3. **Accessibility**
   - Include proper ARIA labels
   - Ensure keyboard navigation support
   - Maintain proper heading hierarchy
   - Add alt text for images

4. **Documentation**
   - Add JSDoc comments for the component
   - Document all props with descriptions
   - Include usage examples in comments
   - Add README.md if component is complex

5. **Testing**
   - Write unit tests for the component
   - Test different prop combinations
   - Test user interactions
   - Ensure accessibility compliance

## Output Format

Provide the following files:

- `ComponentName.jsx` - Main component file
- `ComponentName.css` - Component styles
- `ComponentName.test.jsx` - Test file (optional but recommended)

## Guardrails

- Do NOT use class components
- Do NOT inline large style objects
- Do NOT skip prop validation
- Do NOT ignore accessibility requirements
- Do NOT create duplicate functionality that exists elsewhere

## Example Structure

```jsx
/**
 * ComponentName - Brief description
 *
 * @param {Object} props - Component props
 * @param {string} props.title - The component title
 * @param {Function} props.onClick - Click handler
 * @returns {JSX.Element}
 */
const ComponentName = ({ title, onClick }) => {
  // Implementation
};

export default ComponentName;
```
