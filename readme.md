# laravel-language-extractor

[![downloadsBadge](https://img.shields.io/npm/dt/laravel-language-extractor?style=for-the-badge)](https://npmjs.com/laravel-language-extractor)

Extracts all language strings from a Laravel project and generates or updates a language file.

## Installation

```bash
npx laravel-language-extractor
```

## Usage

```bash
npx laravel-language-extractor [options]
```

### Options

| Option | Description | Default |
| --- | --- | --- |
| `--verbose` | Show verbose output | `false` |
| `--silent` | Show no output | `false` |
| `--theme <theme>` | Theme to use for output for [Laravel-Themer](https://github.com/qirolab/laravel-themer) |  |
| `--path <path>` | Path to Laravel project | `.` |
| `--default-file <file>` | Default language file to use | `lang/en.json` |
| `--no-controllers` | Do not extract strings from controllers | `false` |