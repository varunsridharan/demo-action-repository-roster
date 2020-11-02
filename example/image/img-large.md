# img-large
User's avatar image size will be large

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->

<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
[![Forkers repo roster for @varunsridharan/demo-repository-roster](https://raw.githubusercontent.com/varunsridharan/demo-repository-roster/main/.github/roster/img-large-forks/forks.svg?1604323941)](https://github.com/varunsridharan/demo-repository-roster/stargazers)
<!-- REPOSITORY_FORKS:END -->

---

```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_TYPE: "image"
    FORK_OUTPUT_TYPE: "image"
    STARS_OUTPUT_STYLE: "img-large"
    FORK_OUTPUT_STYLE: "img-large"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```