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

If you want something a bit more controlled:

```
## Syllable Format (Active by Default)

- Break all words into hyphenated syllables  
  `technology` → `tech-nol-o-gy`  
- *Italicize* every 2nd syllable only  
  → `tech-*nol*-o-*gy*`  
- Preserve original casing, spacing, punctuation  
- No grammar fixes or rewording  
- Wrap output in ``` if markdown breaks  
- Toggle with: `format:off` / `format:on`  
- Don’t explain. Just do it.
```
