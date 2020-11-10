# no-image
User's avatar image will not be displayed

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->
[![Stargazers repo roster for @varunsridharan/demo-repository-roster](https://raw.githubusercontent.com/varunsridharan/demo-repository-roster/main/examples/roster-images/no-image-stars.svg?1604331834)](https://github.com/varunsridharan/demo-repository-roster/stargazers)
<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
[![Forkers repo roster for @varunsridharan/demo-action-repository-roster](https://raw.githubusercontent.com/varunsridharan/demo-action-repository-roster/main/examples/roster-images/no-image-forks.svg)](https://github.com/varunsridharan/demo-action-repository-roster/stargazers)
<!-- REPOSITORY_FORKS:END -->

---

```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_TYPE: "image"
    FORK_OUTPUT_TYPE: "image"
    STARS_OUTPUT_STYLE: "no-image"
    FORK_OUTPUT_STYLE: "no-image"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```