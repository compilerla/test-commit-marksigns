# test-commit-marksigns

Testing [`conventional-pre-commit`](https://github.com/compilerla/conventional-pre-commit) with commit messages containing
various "mark signs".

See <https://github.com/compilerla/conventional-pre-commit/issues/15>

## Single quote

```bash
git commit -m "docs: try a commit with a ' (single quote)"
```

## Double quote

```bash
git commit -m "docs: try a commit with a \" (escaped double quote)"
```

## Backtick

```bash
git commit -m "docs: try a commit with a \` (escaped backtick)"
```
