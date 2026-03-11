# CSS Instructions  
applyTo: "**/*.css"

## CSS Best Practices
- Use mobile-first responsive design approach
- Prefer CSS Grid and Flexbox for layouts
- Use CSS custom properties (variables) for consistent theming
- Keep specificity low - avoid deep nesting

## Naming Conventions
- Use kebab-case for class names and IDs
- Use semantic class names that describe purpose, not appearance
- Prefix component-specific classes when needed
- Use BEM methodology for complex components

## Code Organization
- Group related styles together
- Use consistent indentation (2 or 4 spaces)
- Add comments in Portuguese for complex sections
- Order properties logically (layout, styling, animation)

## Performance
- Minimize use of expensive properties (box-shadow, transforms on non-composited elements)
- Use efficient selectors - avoid universal selectors
- Optimize for repaints and reflows
- Use CSS containment when appropriate

## Responsive Design
- Use relative units (rem, em, %, vh/vw) appropriately
- Design breakpoints based on content, not devices
- Test on various screen sizes
- Ensure touch targets are at least 44px

## Accessibility
- Maintain good color contrast ratios
- Don't rely solely on color to convey information
- Ensure focus indicators are visible
- Use proper heading hierarchy styling

## Comments
- Use Portuguese for CSS comments
- Document color schemes and design decisions
- Explain complex calculations or hacks