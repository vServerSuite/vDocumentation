# Installation

## Initial Setup

- Download the `vBungee.jar` from our deployment site [here](https://deployment.vsuite.dev)
- Navigate to your `/plugins/` folder on your **BungeeCord** server and upload `vBungee.jar` into there.
- Fully stop your server and start it up again. *(This allows for the default configuration to be generated)*
- Fully stop your server so you can edit the config.yml located under `/plugins/vBungee/config.yml`
- Read through the configuration file and change the settings to your liking.

!!! note "Database Settings"
    The settings under `Database` **MUST** be setup before you can use this plugin.

## Discord

- Navigate to [Discord Developer Applications](https://discordapp.com/developers/applications) and setup a Bot
  - Go to `Bot` and click `Add Bot`, this will ask you whether you want to add a bot, click `Yes, do it!`
  - Note down the `Bot Token` e.g. `NzAxJATyNTYwMAUAWIUyNTc1.XdARfA.7bSEHZq4kW9yr_vmGawLbBA-UhQ`

!!! note "Discord Channels & Roles"
    Please make sure that the Discord Text Channels & Roles are already created before enabling the discord feature

## Web API

By default, the WebAPI feature is disabled. This feature allows for requests to be made from `vPanel` to check the status of users and to issue punishments

When the WebAPI is first enabled, a Secret will be generated which can be used on the `vPanel`.

## Error Logging

vSuite uses [Sentry.io](https://sentry.io/) for custom error handling. If you would like any errors that may be produced to be sent to the vSuite team, please join our [Discord](https://discord.vsuite.dev) and create a new ticket in the Support category.
