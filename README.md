# 🐱 yuumi.starship

A pastel [Starship](https://starship.rs) prompt theme inspired by **Yuumi**, the Magical Cat from League of Legends — lavender fur, sky-blue eyes, and gold magic.

Fan-made palette. Not affiliated with or endorsed by Riot Games.

## Palette

| Name  | Hex       | Used for                          |                                                                        |
| ----- | --------- | ---------------------------------- | ---------------------------------------------------------------------- |
| iris  | `#a6a0de` | OS icon, jobs                      | ![#a6a0de](https://img.shields.io/badge/-a6a0de-a6a0de?style=flat-square) |
| foam  | `#8fcbe8` | current directory, success symbol  | ![#8fcbe8](https://img.shields.io/badge/-8fcbe8-8fcbe8?style=flat-square) |
| rose  | `#f5a9c5` | language & tool badges (python, node, docker...) | ![#f5a9c5](https://img.shields.io/badge/-f5a9c5-f5a9c5?style=flat-square) |
| gold  | `#efc873` | staged files, custom env           | ![#efc873](https://img.shields.io/badge/-efc873-efc873?style=flat-square) |
| pine  | `#5b4e8c` | git branch                         | ![#5b4e8c](https://img.shields.io/badge/-5b4e8c-5b4e8c?style=flat-square) |
| love  | `#e88fa3` | git status, error symbol           | ![#e88fa3](https://img.shields.io/badge/-e88fa3-e88fa3?style=flat-square) |
| text  | `#f7f3ea` | base text                          | ![#f7f3ea](https://img.shields.io/badge/-f7f3ea-f7f3ea?style=flat-square) |
| muted | `#7a749e` | frame brackets                     | ![#7a749e](https://img.shields.io/badge/-7a749e-7a749e?style=flat-square) |

## Preview

_Add a screenshot of your terminal here — drop a `preview.png` in this folder and it'll show up when you link it below:_

```md
![preview](preview.png)
```

## Install

1. Copy `yuumi.toml` to your Starship config location:
   ```bash
   cp yuumi.toml ~/.config/starship.toml
   ```
2. Make sure Starship is initialized in your shell rc (`~/.zshrc` or `~/.bashrc`):
   ```bash
   eval "$(starship init zsh)"
   ```
3. Reload your shell:
   ```bash
   exec zsh
   ```

You'll need a [Nerd Font](https://www.nerdfonts.com) installed and set as your terminal font for the icons to render correctly.

### Try it without overwriting your current config

```bash
STARSHIP_CONFIG=/path/to/yuumi.toml starship prompt
```

## License

MIT
