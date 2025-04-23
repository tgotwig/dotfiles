# dotfiles

Run `task` to create symlinks via [GNU Stow](https://www.gnu.org/software/stow) and hardlinks via a custom [hardlinks.json](hardlinks.json) file:

```json
[
  {
    "source": "<SOURCE-1>",
    "target": "<TARGET-1>"
  },
  {
    "source": "<SOURCE-2>",
    "target": "<TARGET-2>"
  }
]
```
