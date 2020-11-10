# no-link
Github user's profile link will not be added

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->
<table><tbody><tr><td align="center"><img src="https://avatars3.githubusercontent.com/u/15326217?v=4" alt="@kkotha82" style="max-width:100%;" width="75px;"><br/>@kkotha82</td></tr></tbody></table><p align="center"><i><b>1</b> have starred this repository</i></p>
<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
<table><tbody><tr><td align="center"><img src="https://avatars3.githubusercontent.com/u/15326217?v=4" alt="@kkotha82" style="max-width:100%;" width="75px;"><br/>@kkotha82</td></tr></tbody></table><p align="center"><i><b>1</b> have forked this repository</i></p>
<!-- REPOSITORY_FORKS:END -->

---

```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_STYLE: "no-link"
    FORK_OUTPUT_STYLE: "no-link"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```