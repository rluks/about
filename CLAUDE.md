# Claude Code Instructions - Modern Web Development

## Core Principles
- **Semantic HTML first** - proper document structure and accessibility
- **Progressive enhancement** - core functionality works without JS
- **Mobile-first responsive design** - design for constraints first
- **Performance by default** - optimize images, minimize layout shifts
- **Clean, maintainable code** - consistent naming, clear organization

## CSS Guidelines
- Use modern layout (Grid/Flexbox) over floats or positioning hacks
- Implement consistent design system with CSS custom properties
- Write mobile-first media queries with `min-width`
- Follow DRY principle - extract common patterns into utilities
- Use semantic class names (BEM or similar methodology)
- **NEVER** use inline styles in HTML (`<style>` tags or `style=""` attributes)
- **ALWAYS** put all CSS in the external `styles.css` file

## JavaScript Best Practices
- Use modern ES features when appropriate (modules, async/await, optional chaining)
- Implement proper error handling and loading states
- Prefer native APIs over heavy libraries when possible
- Write self-documenting code with meaningful names

## When Working on This Project
- Follow existing code patterns and conventions
- Test changes across different screen sizes
- Ensure accessibility with proper focus management
- Optimize for performance without over-engineering
- Apply DRY principle to avoid code duplication

## Project Structure
- HTML: `index.html`
- CSS: `css/styles.css` 
- Fonts: `fonts/` directory (Inter Variable)
- Images: `images/` directory (SVGs, photos)

## Flexibility Notes
- Break rules when project constraints require it
- Prioritize user experience over perfect code architecture
- Ask for clarification when requirements conflict with best practices