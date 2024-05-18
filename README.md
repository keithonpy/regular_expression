# Regular Expression Cheat Sheet

## Anchors
Anchors match a position before or after other characters
| Syntax | Usage | Example| matches|
|------|-----|------|-------|
|`^` or `\A` |match start of line|`^`r or `\A`r| rose|
|`$` or `\Z`|match end of line| t`$` or t`\Z`| submit|
|`\b`|word boundary, match characters at the start or end of a word|`\b`fox, `\b`fox`\b`| foxInn, fox|
|`\B`|match any position between word that is **not** word boundary |`\B`ex`\B`|Text|
