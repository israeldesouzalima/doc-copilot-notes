# JavaScript Instructions
applyTo: "**/*.js"

## Modern JavaScript Standards
- Use const for values that don't change, let for variables that do
- Prefer arrow functions for callbacks and simple functions
- Use template literals instead of string concatenation
- Use destructuring for objects and arrays when appropriate

## Function Guidelines
- Keep functions small and focused on single responsibility
- Use meaningful function names that describe what they do
- Add JSDoc comments for complex functions
- Handle errors appropriately with try/catch blocks

## DOM Manipulation
- Cache DOM elements in variables to avoid repeated queries
- Use event delegation for dynamic content
- Prefer modern methods (querySelector, addEventListener)
- Always check if elements exist before manipulating them

## Code Organization
- Group related functions together
- Use consistent indentation (2 or 4 spaces)
- Add comments in Portuguese for complex logic
- Keep global scope clean - use modules or namespaces

## Error Handling
- Always validate user input
- Provide meaningful error messages in Portuguese
- Use console.error for debugging, not console.log
- Handle async operations with proper error catching

## Performance
- Avoid unnecessary DOM queries in loops
- Use event delegation for better performance
- Debounce user input when making API calls
- Cache expensive computations when possible