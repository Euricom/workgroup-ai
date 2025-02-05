# Here are some cursor rules for different technologies:

## Express.js and TypeScript

```
You are an expert in Express.js, TypeScript, and Node.js development.

Code Style and Structure:
- Write concise, efficient TypeScript code for Express.js applications
- Use functional programming patterns where appropriate
- Organize routes, middleware, and controllers in separate files
- Use descriptive variable names and follow camelCase convention

TypeScript Usage:
- Utilize TypeScript for all server-side code
- Define interfaces for request and response objects
- Use type annotations for function parameters and return types

Express.js Best Practices:
- Implement proper error handling middleware
- Use async/await for asynchronous operations
- Organize routes logically and use Express Router
- Implement input validation for API endpoints

Development Workflow:
- Use tsx for automatic server restarts during development
- Follow the scripts defined in package.json for building and running the application

Performance and Security:
- Implement proper error logging
- Use environment variables for sensitive information
- Implement rate limiting and other security measures as needed

Testing:
- Write unit tests for controllers and services
- Implement integration tests for API endpoints

Documentation:
- Maintain clear and up-to-date API documentation
- Use JSDoc comments for functions and classes

Dependency Management:
- Keep dependencies up-to-date, especially Express and TypeScript
- Use yarn for package management as specified in the project

Follow Express.js and Node.js best practices for RESTful API development
```

## NextJS, App Router, React, Shadcn UI, Radix UI, and Tailwind


```
You are an expert in TypeScript, Node.js, Next.js App Router, React, Shadcn UI, Radix UI and Tailwind.

Code Style and Structure
- Write concise, technical TypeScript code with accurate examples.
- Use functional and declarative programming patterns; avoid classes.
- Prefer iteration and modularization over code duplication.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError).
- Structure files: exported component, subcomponents, helpers, static content, types.

Naming Conventions
- Use lowercase with dashes for directories (e.g., components/auth-wizard).
- Favor named exports for components.

TypeScript Usage
- Use TypeScript for all code; prefer interfaces over types.
- Avoid enums; use maps instead.
- Use functional components with TypeScript interfaces.

Syntax and Formatting
- Use the "function" keyword for pure functions.
- Avoid unnecessary curly braces in conditionals; use concise syntax for simple statements.
- Use declarative JSX.

UI and Styling
- Use Shadcn UI, Radix, and Tailwind for components and styling.
- Implement responsive design with Tailwind CSS; use a mobile-first approach.

Performance Optimization
- Minimize 'use client', 'useEffect', and 'setState'; favor React Server Components (RSC).
- Wrap client components in Suspense with fallback.
- Use dynamic loading for non-critical components.
- Optimize images: use WebP format, include size data, implement lazy loading.

Key Conventions
- Use 'nuqs' for URL search parameter state management.
- Optimize Web Vitals (LCP, CLS, FID).
- Limit 'use client':
  - Favor server components and Next.js SSR.
  - Use only for Web API access in small components.
  - Avoid for data fetching or state management.

Follow Next.js docs for Data Fetching, Rendering, and Routing.
```

## NextJS, App Router, React, Shadcn UI, Radix UI, and Tailwind

```
You are an expert in TypeScript, Node.js, Next.js App Router, React, Shadcn UI, Radix UI and Tailwind.

Code Style and Structure
- Write concise, technical TypeScript code with accurate examples.
- Use functional and declarative programming patterns; avoid classes.
- Prefer iteration and modularization over code duplication.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError).
- Structure files: exported component, subcomponents, helpers, static content, types.

Naming Conventions
- Use lowercase with dashes for directories (e.g., components/auth-wizard).
- Favor named exports for components.

TypeScript Usage
- Use TypeScript for all code; prefer interfaces over types.
- Avoid enums; use maps instead.
- Use functional components with TypeScript interfaces.

Syntax and Formatting
- Use the "function" keyword for pure functions.
- Avoid unnecessary curly braces in conditionals; use concise syntax for simple statements.
- Use declarative JSX.

UI and Styling
- Use Shadcn UI, Radix, and Tailwind for components and styling.
- Implement responsive design with Tailwind CSS; use a mobile-first approach.

Performance Optimization
- Minimize 'use client', 'useEffect', and 'setState'; favor React Server Components (RSC).
- Wrap client components in Suspense with fallback.
- Use dynamic loading for non-critical components.
- Optimize images: use WebP format, include size data, implement lazy loading.

Key Conventions
- Use 'nuqs' for URL search parameter state management.
- Optimize Web Vitals (LCP, CLS, FID).
- Limit 'use client':
  - Favor server components and Next.js SSR.
  - Use only for Web API access in small components.
  - Avoid for data fetching or state management.

Follow Next.js docs for Data Fetching, Rendering, and Routing.
```

## CSS

```
# CSS
- Follow BEM (Block, Element, Modifier) methodology for class naming.
- Use Flexbox or Grid for layout purposes.
- Implement responsive design using media queries.
- Use variables for colors, spacing, and font sizes.
```

## NodeJS

```
# Node.js
- Follow common JavaScript/Node.js best practices.
- Use ES6+ features (e.g., arrow functions, destructuring).
- Handle asynchronous operations using async/await.
- Use environment variables for configuration.
- Structure code into modules for better maintainability.
- Write comprehensive error handling and logging (use a logging library like Winston if needed).
```

## TypeScript

```
# TypeScript Usage
- Enable strict TypeScript (strict: true in tsconfig.json)
- Avoid 'any', prefer 'unknown' with runtime checks
- Explicitly type function inputs and outputs
- Use advanced TypeScript features (type guards, mapped types, conditional types)
```

## Tailwind

```
TailwindCSS and DaisyUI Rules:
- Use TailwindCSS utility classes for styling
- Avoid custom CSS unless absolutely necessary
- Maintain consistent order of utility classes
- Use Tailwind's responsive variants for adaptive designs
- Define and use design tokens in tailwind.config.js
```

## DaisyUI

```
- Leverage DaisyUI components for rapid development
- Customize DaisyUI components only when necessary
```
