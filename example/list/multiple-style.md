# bold,italic,list-ordered
Username will be bold & italic & Users list will be generated using HTML `ol` _Ordered list_

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->

<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->
<table><tbody><tr><td align="center"><a href="https://github.com/technofreaky" rel="nofollow"><img src="https://avatars1.githubusercontent.com/u/32121790?v=4" alt="@technofreaky" style="max-width:100%;" width="75px;"><br/><b><i>@technofreaky</i></b></a> </td><td align="center"><a href="https://github.com/anirudhdhan" rel="nofollow"><img src="https://avatars2.githubusercontent.com/u/68533015?v=4" alt="@anirudhdhan" style="max-width:100%;" width="75px;"><br/><b><i>@anirudhdhan</i></b></a> </td><td align="center"><a href="https://github.com/aanmeegasaaral" rel="nofollow"><img src="https://avatars0.githubusercontent.com/u/66984783?v=4" alt="@aanmeegasaaral" style="max-width:100%;" width="75px;"><br/><b><i>@aanmeegasaaral</i></b></a> </td><td align="center"><a href="https://github.com/kkotha82" rel="nofollow"><img src="https://avatars3.githubusercontent.com/u/15326217?v=4" alt="@kkotha82" style="max-width:100%;" width="75px;"><br/><b><i>@kkotha82</i></b></a> </td></tr></tbody></table><p align="center"><i><b>4</b> have forked this repository</i></p>
<!-- REPOSITORY_FORKS:END -->

---

```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_TYPE: "list"
    FORK_OUTPUT_TYPE: "list"
    STARS_OUTPUT_STYLE: "bold,italic,list-ordered"
    FORK_OUTPUT_STYLE: "bold,italic,list-ordered"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```