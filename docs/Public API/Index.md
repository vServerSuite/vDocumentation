
# Public API

## Introduction

We provide a simple API for developers to access our release files.  This includes all modules including vPanel.

## Usage

The base URL for the API is `https://files.vsuite.dev` - a key usage of this system would be to build a custom auto-updater system.

### Endpoints

| Endpoint                       | Method | Description                                    |
|--------------------------------|--------|------------------------------------------------|
| /\<module>/releases            | GET    | Returns a JSON array of all available releases |
| /\<module>/releases/<@version> | GET    | Downloads the relevant file for that release   |

!!! note "File types"
    For all BungeeCord and Minecraft plugins, a .jar file is returned.  In the case of vPanel, however, a zip containing the installation files will be sent.

### Errors

In most cases errors will be verbose and correctable, however in the event that an unknown error occurs an "Issue ID" will be returned and we ask that you contact us for more help.
