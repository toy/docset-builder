# Dash docset builder

```yaml
jobs:
  build:
    permissions:
      contents: write
    uses: toy/docset-builder/.github/workflows/build.yml@main
    with:
      cache-path: |
        some-path
    secrets:
      DASH_USER_CONTRIBUTIONS_PAT: ${{ secrets.DASH_USER_CONTRIBUTIONS_PAT }}
```
