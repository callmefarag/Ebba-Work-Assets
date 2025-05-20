# EBBA Work Assets

This is a repository for work assets used by the EBBA team.

## Projects Prerequisites

- Git
- Node 18+
- Angular CLI 19.2 (Always Updated to latest version)

## Configuration Files & How to use them



### Current Configuration Files

#### Trae AI Configurations:
The Trae AI configuration files contain settings and rules that ensure consistent code generation and formatting across our projects:

`project_rules.md`: Main configuration file that defines coding standards, patterns, and best practices.

These configurations help maintain code quality and consistency when using AI-assisted development.

#### Prettier Configurations:
Prettier is our code formatting tool that automatically formats code to ensure consistent style. The configuration includes:

`.prettierrc`: Contains formatting rules like indentation, line length, quotes style etc.

These settings ensure all team members produce consistently formatted code regardless of their editor or IDE preferences.

### How to Use:
    1. Clone the repository.
    2. Navigate to the folder you want to use.
    3. Copy the files inside the folder to the project root.
    4. Confirm that the configuration is working correctly.

---
## Tech Stack

### Angular

#### Core features:
- Control flow with built-in @if, @for, @switch directives
- Standalone components and routing
- Dependency injection and services
- Component lifecycle hooks

#### Development workflow:
- Angular CLI for scaffolding (--skip-tests flag used)
- Angular DevTools for debugging

#### UI stack:
- Tailwind CSS 4.x for styling
- PrimeNG 19+ for UI components

#### Server-side features:
- Angular SSR.
- New experimental server routes, Which will be in developer preview or stable in Angular 20.
- Hydration and incremental hydration, with `EventReplay`, `withHttpCacheOptions()`.

#### Modern Angular patterns:
- Zone.js-less, No Zone.js at all.
- Usage of `HttpClient`, with new `httpResource` if the feature is just fetching data from the server.
- Route resolvers for single pages (ex: Product Single Page)
- SEO optimization with Meta and Title services is a must.

#### Enhanced styling:
- TailwindCSS Motion plugin
- TailwindCSS Intersection plugin

#### State management:
- Signals for reactive state.
- Input/Output signals.
- Reactive Forms.