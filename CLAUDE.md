# Horizon UI (Next.js + Chakra UI) Commands and Guidelines

## Build/Lint/Test Commands
- `yarn dev` - Start development server
- `yarn build` - Build for production
- `yarn start` - Start production server
- `yarn lint` - Run ESLint
- `yarn test` - Run Jest tests (when added)
- `yarn test:watch` - Run Jest in watch mode (when added)

## Code Style Guidelines

### TypeScript
- Use strict type checking (project has `strict: true`)
- Avoid `any` type when possible
- Use proper interfaces/types
- Follow noImplicitAny and noImplicitThis rules
- Use proper nullability checks

### Formatting & Naming
- Use singleQuote for strings (as per Prettier config)
- Use trailing commas (as per Prettier config)
- Use PascalCase for components and interfaces
- Use camelCase for variables and functions
- Follow Next.js file naming conventions

### Project Structure
- Pages in `/app` directory (Next.js 13+ App Router)
- Components in `/components` directory
- Layouts in `/layouts` directory
- Themes in `/theme` directory
- Utilities in `/utils` directory

### Imports
- Use absolute imports from src (baseUrl is set to src)
- Group imports: React/libraries first, then local modules