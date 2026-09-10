# use-fluent

A handful of React hooks I keep copy-pasting between projects

Side project, maintained when I have time.

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Highlights

- useMediaQuery SSR-safe
- Tiny: no dependencies besides React
- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization

## Install

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
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
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT - see [LICENSE](LICENSE).
