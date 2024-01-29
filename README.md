# nbstripout mirror

Mirror of nbstripout for pre-commit with conda as a language.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For nbstripout: see [here](https://github.com/kynan/nbstripout)

## Using nbstripout with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-nbstripout
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: nbstripout-conda
```
