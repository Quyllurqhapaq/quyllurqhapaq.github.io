---
title: Info commands
description: Command related to info command.
---

# Information Commands
Get information about your server, users, channels etc.

--8<-- "includes/note1.md"

## Command tree
Command tree for info category

```terminal
├── avatar
├── userinfo
├── serverinfo
├── roleinfo
├── botinfo
├── channelinfo
└── voiceinfo
```

## Command description

???+ abstract "Info commands"
    | Command Name       | Aliases          | Usage                      | Description                                 |
    | :----------------- | :--------------- | :------------------------- | :------------------------------------------ |
    | **avatar**         | ava              | $avatar [user]             | Sends user avatar                           |
    | **userinfo**       | uinfo            | $userinfo [user]           | Get information about any user              |
    | **serverinfo**     | sinfo            | $serverinfo                | Shows info about the current server         |
    | **roleinfo**       | rinfo            | $roleinfo <role\>          | Get information on a role                   |
    | **botinfo**        | binfo/stats      | $botinfo                   | Get info about Zarena                       |
    | **channelinfo**    | cinfo            | $channelinfo [channel]     | Displays information about a text channel   |
    | **voiceinfo**      | vinfo            | $voiceinfo [voicechannel]  | Displays information about a voice channel  |