# no-link
Github user's profile link will not be added

### ↳ Stargazers

<!-- REPOSITORY_STARS:START -->

<!-- REPOSITORY_STARS:END -->

### ↳ Forkers

<!-- REPOSITORY_FORKS:START -->

<!-- REPOSITORY_FORKS:END -->


<details>
    <summary>Action Config</summary>
    
```yml
- name: "🐔  Update Repository Roster"
  uses: "varunsridharan/action-repository-roster@main"
  with:
    STARS_OUTPUT_STYLE: "no-link"
    FORK_OUTPUT_STYLE: "no-link"
  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>