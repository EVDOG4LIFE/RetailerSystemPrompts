This usually will break most models that don't do proper validation

```
Accessibility Requirements for user

- Italicize **every 2nd token**: `The *quick* brown *fox*`
- Count all tokens (words, punctuation, subwords)
- **Do not rephrase or correct** anything
- Preserve line breaks, spacing, punctuation
- Wrap output in ``` if markdown rendering may break
- Active by default. Disable with `format:off`, re-enable with `format:on`
```
