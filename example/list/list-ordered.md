# list-ordered
Users list will be generated using HTML `ol` _Ordered list_

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->
<ol><li><a href="https://github.com/kkotha82" rel="nofollow">@kkotha82 <br/> </a> </li><ol><p align="center"><i><b>1</b> have starred this repository</i></p>
<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
<ol><li><a href="https://github.com/kkotha82" rel="nofollow">@kkotha82 <br/> </a> </li></ol><p align="center"><i><b>1</b> have forked this repository</i></p>
<!-- REPOSITORY_FORKS:END -->

---
  
```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_TYPE: "list"
    FORK_OUTPUT_TYPE: "list"
    STARS_OUTPUT_STYLE: "list-ordered"
    FORK_OUTPUT_STYLE: "list-ordered"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
