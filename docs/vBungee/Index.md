# vBungee

## Introduction

## Features

- Punishments *(Bans, Mutes, Kicks)*
- Logging *(Joins, Quits, Chat, Commands)*
- Server Management *(Global Stats, Pterodactyl Integration)*
- Web API for [vPanel](/vPanel/Index/)

## Commands

!!! note "Useful Information"
    Parameters wrapped in `<>` are mandatory for the command
    Parameters wrapped in `[]` are optional for the command

### Management

| Command | Permission   | Description                            |
|---------|--------------|----------------------------------------|
| /bstats | vSuite.stats | Shows the statistics of the BungeeCord |

### Punishments

| Command                            | Permission  | Description                    |
|------------------------------------|-------------|--------------------------------|
| /ban `<user>` `[time]` `<reason>`  | vSuite.ban  | Bans a player from the server  |
| /mute `<user>` `[time]` `<reason>` | vSuite.mute | Mutes a player on the server   |
| /kick `<user>` `<reason>`          | vSuite.kick | Kicks a player from the server |

### General

| Command                       | Permission       | Description                          |
|-------------------------------|------------------|--------------------------------------|
| /lobby                        | vSuite.lobby     | Sends the player to a Lobby          |
| /report `<player>` `<reason>` | vSuite.report    | Reports a player                     |
| /sc `[message]`               | vSuite.staffchat | Sends a message / toggles Staff Chat |