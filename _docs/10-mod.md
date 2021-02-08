---
title: "mod commands"
permalink: /docs/mod/
excerpt: "Command related to moderation."
single_layout_gallery:
  - image_path: /assets/images/mm-layout-single-header.png
    alt: "single layout with header example"
  - image_path: /assets/images/mm-layout-single-meta.png
    alt: "single layout with comments and related posts"
last_modified_at: 2020-08-30T21:27:40-04:00
toc: true
toc_label: "Included Layouts"
toc_icon: "columns"
---

Command tree for mod commands

```terminal
├── mute
├── unmute
├── warn
├── kick
|  └── voicekick
├── ban
|  ├── softban
|  ├── hackban
|  └── massban
├── unban
├── purge
├── lock
├── unlock
├── slowmode
├── addrole
└── removerole
```

### command description

| Command              | Aliases          | Uses                        | Description
| ---------------------| -----------------|-----------------------------|----------------------------------|
| **mute**             | -                | $mute <user>                | Starts a game of hangman         |
| **unmute**           | -                | $unmute <user>              | Starts a game of tictactoe       |
| **warn**             | -                | $warn <user>                | Starts a game of trivia          |
| **kick**             | -                | $kick <user>                | Starts a game of rps             |
| **voicekick**        | wh               | $voicekick <user>           | Starts a game of wordhunt        | 
| **ban**              | -                | $ban <user>                 | Starts a game of scramble        |
| **softban**          | sban             | $softban <user>             | Starts a game of passthebomb     |  
| **hackban**          | hban             | $hackban <user>             | Starts a game of guessthepokemon |
| **massban**          | mban             | $massban <user>             | Starts a game of guessthemovie   |
| **unban**            | uban             | $unban <user>               | Starts a game of bowling         |
| **purge**            | prune            | $purge <amount>             | Starts a game of wordhunt        | 
| **lock**             | -                | $lock [channel]             | Starts a game of scramble        |
| **unlock**           | -                | $unlock [channel]           | Starts a game of passthebomb     |  
| **slowmode**         | slow             | $slowmode [time]            | Starts a game of guessthepokemon |
| **addrole**          | arole            | $addrole <user> <role>      | Starts a game of guessthemovie   |
| **removerole**       | role             | $removerole <user> <role>   | Starts a game of bowling         |
