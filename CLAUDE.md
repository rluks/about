# Claude Code Instructions

## CSS Guidelines
- **NEVER** use inline styles in HTML (`<style>` tags or `style=""` attributes)
- **ALWAYS** put all CSS in the external `styles.css` file
- If you find inline styles, move them to the CSS file immediately
- Use semantic CSS classes and maintain existing naming conventions

## DRY Principle (Don't Repeat Yourself)
- **ALWAYS** extract common properties into shared CSS selectors
- **NEVER** duplicate identical CSS properties across multiple rules
- Create shared classes or grouped selectors for common styling patterns
- Example: `.selector1, .selector2 { /* shared properties */ }`
- Only define unique properties separately for each selector
- This makes the code more maintainable and allows easy global adjustments

## Project Structure
- HTML: `index.html`
- CSS: `css/styles.css` 
- Fonts: `fonts/` directory (Inter Variable)
- Images: `images/` directory (SVGs, photos)

## Development Practices
- Follow existing code patterns and conventions
- Use CSS variables for consistent styling
- Maintain responsive design principles
- Apply DRY principle to avoid code duplication
- Test changes thoroughly before completion