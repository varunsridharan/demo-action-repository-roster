# bold
Username text will be bold

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->
[![Stargazers repo roster for @varunsridharan/demo-action-repository-roster](https://raw.githubusercontent.com/varunsridharan/demo-action-repository-roster/main/examples/roster-images/bold-stars.svg)](https://github.com/varunsridharan/demo-action-repository-roster/stargazers)
<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
[![Forkers repo roster for @varunsridharan/demo-action-repository-roster](https://raw.githubusercontent.com/varunsridharan/demo-action-repository-roster/main/examples/roster-images/bold-forks.svg)](https://github.com/varunsridharan/demo-action-repository-roster/stargazers)
<!-- REPOSITORY_FORKS:END -->

---

```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_TYPE: "image"
    FORK_OUTPUT_TYPE: "image"
    STARS_OUTPUT_STYLE: "bold"
    FORK_OUTPUT_STYLE: "bold"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```