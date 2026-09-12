# use-fluent

Small typed hooks: debounce, localStorage, media query, toggle

## Getting started

```bash
npm install
npm test
```

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## What it does

- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- Tiny: no dependencies besides React
- useLocalStorage with JSON serialization

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Notes

- mostly stable, edge cases remain

## License

MIT. Do whatever you want.
