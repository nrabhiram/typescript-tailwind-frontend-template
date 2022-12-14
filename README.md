# Typescript Tailwind Frontend Template

This template has been configured with all of the tools required to create a Single Page Application (SPA) using **vanilla TypeScript** and **TailwindCSS**.

List of tools:

- [TypeScript](https://www.typescriptlang.org/)
- [TailwindCSS](https://tailwindcss.com/) for utility CSS classes
- [ESLint](https://eslint.org/) configured with some initial rules
- [Prettier](https://prettier.io/) to enforce consistent code style
- [Vitest](https://vitest.dev/) for unit testing and code coverage
- [Webpack](https://webpack.js.org/) to compile TS code to JS, generate a bundle file, and build the project files for distribution

## Development

### Setup

1. `git clone https://github.com/nrabhiram/typescript-tailwind-frontend-template.git`
2. Run `npm install` to install all of the project's dependencies
3. Build the project for development: `npm run build-dev`
4. Run the local development server: `npm run start`

### Dev Loop

- `prettier-format` - run the autoformatter
- `lint` - run the linter
- `test` - run the specs
- `test-filter <spec-name>` - run a specific spec
- `coverage` - get a coverage report of the specs
- `build` - build the project files for distribution
- `build-dev` - build the project files for development
- `start` - run the local development server

## License

The project is available as open source under the terms of the [MIT License](LICENSE).
