<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- @generated by .automation/build.py, please do not update manually -->
<!-- Instead, update descriptor file at https://github.com/megalinter/megalinter/tree/main/megalinter/descriptors/typescript.yml -->
# TYPESCRIPT

## Linters

| Linter                             | Configuration key                             | Status                                                                                                                             |
|------------------------------------|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| [eslint](typescript_eslint.md)     | [TYPESCRIPT_ES](typescript_eslint.md)         | [![GitHub last commit](https://img.shields.io/github/last-commit/eslint/eslint)](https://github.com/eslint/eslint/commits)         |
| [standard](typescript_standard.md) | [TYPESCRIPT_STANDARD](typescript_standard.md) | [![GitHub last commit](https://img.shields.io/github/last-commit/standard/standard)](https://github.com/standard/standard/commits) |
| [prettier](typescript_prettier.md) | [TYPESCRIPT](typescript_prettier.md)          | [![GitHub last commit](https://img.shields.io/github/last-commit/prettier/prettier)](https://github.com/prettier/prettier/commits) |

## Linted files

- File extensions:
  - `.ts`

## Configuration in MegaLinter

| Variable                        | Description                   | Default value |
|---------------------------------|-------------------------------|---------------|
| TYPESCRIPT_FILTER_REGEX_INCLUDE | Custom regex including filter |               |
| TYPESCRIPT_FILTER_REGEX_EXCLUDE | Custom regex excluding filter |               |


## Behind the scenes

### Installation

- NPM packages (node.js):
  - [typescript](https://www.npmjs.com/package/typescript)