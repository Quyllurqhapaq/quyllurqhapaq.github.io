---
title: Mod commands
description: Command related to moderation.
---

# Moderation Commands
Powerful moderation commands so that you can monitor your server properly.

--8<-- "includes/note1.md"

## Command tree
Command tree for mod commands

```terminal
├── prefix
├── mute
├── unmute
├── warn
├── kick
|  └── voicekick
├── ban
|  ├── softban
|  └── hackban
├── unban
├── purge
├── lock
├── unlock
├── slowmode
├── addrole
└── removerole
```

## Command description

???+ abstract "Moderation commands"
    | Command Name     | Aliases        | Uses                         | Description                                                         |
    | :--------------- | :------------- | :--------------------------- | :------------------------------------------------------------------ |
    | **prefix**       | -              | $prefix [prefix]             | Get or change (server owner only) the prefix of the server you're in|
    | **mute**         | -              | $mute <user\>                | Mutes a user. Time limit is in minutes.                             |
    | **unmute**       | -              | $unmute <user\>              | Unmute a user from the server                                       |
    | **warn**         | -              | $warn <user\>                | Gives warning to a user                                             |
    | **kick**         | -              | $kick <user\>                | Kick a user from the server                                         |
    | **voicekick**    | -              | $voicekick <user\>           | Kick a user from a voice channel                                    |
    | **ban**          | -              | $ban <user\>                 | Bans a person from the guild                                        |
    | **softban**      | sban           | $softban <user\>             | Kicks a user and deletes their messages                             |
    | **hackban**      | hban           | $hackban <userid\>           | Bans a user by id who is currently not in the server                |
    | **unban**        | uban           | $unban <user\>               | Unban a user from the server                                        |
    | **purge**        | prune/clear    | $purge <amount\>             | Deletes messages from current channel                               |
    | **lock**         | -              | $lock [channel]              | Locks the given channel                                             |
    | **unlock**       | -              | $unlock [channel]            | Unlocks the given channel                                           |
    | **slowmode**     | slow           | $slowmode [time]             | Set slowode in a channel                                            |
    | **addrole**      | arole          | $addrole <user\> <role\>     | Adds role to a user                                                 |
    | **removerole**   | rrole          | $removerole <user\> <role\>  | Removes a role from user                                            |