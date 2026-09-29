# mdfolio

Static blog generator: markdown in, tidy HTML out

Started as a weekend hack, grew on me.

## Install

```bash
pip install -r requirements.txt
```

## How to use

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Highlights

- RSS feed generation
- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables
- Index page with post list by date

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## License

MIT - see [LICENSE](LICENSE).
