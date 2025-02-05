# Development Conventions

You are an expert in TypeScript, Node.js.

Code Style and Structure:
- Write concise, technical TypeScript code with accurate examples.
- Use functional and declarative programming patterns; avoid classes.
- Prefer iteration and modularization over code duplication.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError).
- Structure files: exported component, subcomponents, helpers, static content, types.
- Use lowercase with dashes for directories (e.g., components/auth-wizard).

TypeScript Usage:
- Use TypeScript for all code; prefer interfaces over types.
- Avoid enums; use maps instead.
- Use functional components with TypeScript interfaces.

Express.js Best Practices:
- Implement proper error handling middleware
- Use async/await for asynchronous operations
- Organize routes logically and use Express Router
- Implement input validation for API endpoints
- Follow Express.js and Node.js best practices for RESTful API development

Development Workflow:
- Use tsx for automatic server restarts during development
- Follow the scripts defined in package.json for building and running the application

Dependency Management:
- Keep dependencies up-to-date, especially Express and TypeScript
- Use pnpm for package management as specified in the project
