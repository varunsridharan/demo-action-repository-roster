# bold
Username text will be bold

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->
<ul><li><a href="https://github.com/varunsridharan" rel="nofollow"><b>@varunsridharan</b> <br/> </a> </li><li><a href="https://github.com/kkotha82" rel="nofollow"><b>@kkotha82</b> <br/> </a> </li><ul><p align="center"><i><b>2</b> have starred this repository</i></p>
<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
<ul><li><a href="https://github.com/technofreaky" rel="nofollow"><b>@technofreaky</b> <br/> </a> </li><li><a href="https://github.com/anirudhdhan" rel="nofollow"><b>@anirudhdhan</b> <br/> </a> </li><li><a href="https://github.com/aanmeegasaaral" rel="nofollow"><b>@aanmeegasaaral</b> <br/> </a> </li><li><a href="https://github.com/kkotha82" rel="nofollow"><b>@kkotha82</b> <br/> </a> </li><ul><p align="center"><i><b>4</b> have forked this repository</i></p>
<!-- REPOSITORY_FORKS:END -->

---

```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_TYPE: "list"
    FORK_OUTPUT_TYPE: "list"
    STARS_OUTPUT_STYLE: "bold"
    FORK_OUTPUT_STYLE: "bold"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```