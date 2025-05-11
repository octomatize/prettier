# @octomatize/prettier

A shared Prettier configuration package for projects, featuring Tailwind CSS class sorting and consistent code formatting rules.

## Features

- Pre-configured Prettier settings for consistent code formatting
- Built-in support for Tailwind CSS class sorting
- Optimized for modern JavaScript/TypeScript development
- Published as a GitHub Package

## Installation

```bash
npm install --save-dev @octomatize/prettier
```

```bash
pnpm add --dev @octomatize/prettier
```

## Usage

Create a `.prettierrc.js` file in your project root:

```javascript
module.exports = require('@octomatize/prettier')
```

Or extend it in your existing Prettier configuration:

```javascript
module.exports = {
  ...require('@octomatize/prettier'),
  // Add your custom overrides here
}
```

## Configuration

This package includes the following default configuration:

- Print width: 80 characters
- Tab width: 2 spaces
- No semicolons
- Single quotes
- Trailing commas in ES5 mode
- Bracket spacing enabled
- Arrow function parentheses always
- Auto line endings
- Tailwind CSS class sorting

## Development

This package is published to GitHub Packages. Make sure you have the following in your `.npmrc`:

```
@octomatize:registry=https://npm.pkg.github.com/
```

## License

MIT
