# bold,italic,img-rounded,img-small
Username will be bold & italic & User's avatar will be small

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->
[![Stargazers repo roster for @varunsridharan/demo-repository-roster](https://raw.githubusercontent.com/varunsridharan/demo-repository-roster/main/.github/roster/multiple-style-stars/stars.svg?1604330778)](https://github.com/varunsridharan/demo-repository-roster/stargazers)
<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
[![Forkers repo roster for @varunsridharan/demo-repository-roster](https://raw.githubusercontent.com/varunsridharan/demo-repository-roster/main/.github/roster/multiple-style-forks/forks.svg?1604330777)](https://github.com/varunsridharan/demo-repository-roster/stargazers)
<!-- REPOSITORY_FORKS:END -->

---

```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_TYPE: "image"
    FORK_OUTPUT_TYPE: "image"
    STARS_OUTPUT_STYLE: "img-rounded,img-small,bold,italic"
    FORK_OUTPUT_STYLE: "img-rounded,img-small,bold,italic"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```