---
title: "Mod commands"
permalink: /docs/mod/
excerpt: "Command related to moderation."
last_modified_at: 2020-08-30T21:27:40-04:00
toc: true
toc_label: "On this page"
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

### Command description

| Command              | Aliases          | Uses                        | Description
| ---------------------| -----------------|-----------------------------|-------------------------------------------|
| **mute**             | -                | $mute <user>                | Mutes a user. Time limit is in minutes.   |
| **unmute**           | -                | $unmute <user>              | unmute a user                             |
| **warn**             | -                | $warn <user>                | warn a user                               |
| **kick**             | -                | $kick <user>                | kick a user                               |
| **voicekick**        | -                | $voicekick <user>           | voicekick a user                          | 
| **ban**              | -                | $ban <user>                 | ban a user                                |
| **softban**          | sban             | $softban <user>             | softban a user                            |  
| **hackban**          | hban             | $hackban <user>             | hackban a user by id                      |
| **massban**          | mban             | $massban <user>             | massban users                             |
| **unban**            | uban             | $unban <user>               | unban a user                              |
| **purge**            | prune            | $purge <amount>             | deletes messages from current channel     | 
| **lock**             | -                | $lock [channel]             | Lock a channel                            |
| **unlock**           | -                | $unlock [channel]           | Unlock a channel                          |  
| **slowmode**         | slow             | $slowmode [time]            | Manage slowode of a channel               |
| **addrole**          | arole            | $addrole <user> <role>      | Add role to user                          |
| **removerole**       | rrole            | $removerole <user> <role>   | Remove a role from user                   |
