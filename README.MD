# D2R PVPGN PROXY LAYER - ALPHA

![proxy scheme](res/conn_scheme.png)

## What is proxy layer

The proxy work as is a compatibility layer between the packets and commands of a modern client version and the [PvPGN](https://ru.wikipedia.org/wiki/PvPGN) server.

## Features

- Deploy own Dedicated Server.
- LAN game with local server.
- Configurable.
- Technically it supports mods.

## Limitation

- Supported client: product version *1.5.73090* / file version *1.5.7554.0*.
- Only the first act are available.
- Chat channels are not fully supported.

## Installation

### Prepare Server

1. Deploy [PvPGN](https://github.com/pvpgn/pvpgn-server) with [D2GS](https://pvpgn.pro/d2gs_installation.html).

2. Copy the `d2gs/Patch_D2.mpq` and replace it in the D2GS directory (use `Patch_D2.mpq` as base for mods).

### Prepare Client

3. Copy `bin/D2PLR.exe` and `bin/blizzless.ini` to the main client directory.
4. Set IP address and port of your PVPGN in `blizzless.ini` file.
5. Run `D2PLR.exe` and enter your *login* and *password* (You can enable auto-registration in PvPGN).
