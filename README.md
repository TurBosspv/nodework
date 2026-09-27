# nodework

Small TypeScript CLI: CSV to JSON converter

## Examples

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Install

```bash
npm install
npm run build
```

## Highlights

- Ships as an ESM binary
- Strict tsconfig, no any
- commander-based subcommands
- npm link friendly

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas
