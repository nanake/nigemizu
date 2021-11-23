# Mirror Master

A Github Action for mirroring

## Typical usage

```yml
# .github/workflows/mirroring.yml

jobs:
  mirroring:
    runs-on: ubuntu-latest
    steps:
    - uses: nanake/nigemizu@main
      with: # all args are required
        source: https://source.repo.git
        target: github-taget-repo-name
        token: ${{ secrets.personal-access-token }}
```
