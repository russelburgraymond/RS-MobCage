# Installation

This guide explains how to install RS-MobCages on your Paper Minecraft server.

---

## Requirements

Before installing RS-MobCages, make sure your server meets the plugin requirements.

- A supported version of Paper
- A compatible Java version for your Minecraft server
- Permission to install plugins on the server

RS-MobCages is designed for Paper servers.

---

## Installing RS-MobCages

### Step 1 — Stop Your Server

Before installing or updating any plugin, stop your Minecraft server completely.

---

### Step 2 — Download RS-MobCages

Download the latest release of RS-MobCages from one of the supported download locations.
Place the downloaded `.jar` file somewhere you can easily access.

---

### Step 3 — Install the Plugin

Move the RS-MobCages `.jar` file into your server's:

    plugins/

folder.

Your server directory should look similar to:

    server/
    ├── plugins/
    │   ├── RS-MobCages.jar
    │   └── ...
    ├── world/
    ├── world_nether/
    └── world_the_end/

---

### Step 4 — Start Your Server

Start the Minecraft server normally.
During startup, Paper will load RS-MobCages and create any required plugin files.
After the server has finished starting, check the console for the RS-MobCages startup message.

---

## Verifying Installation

Join the server and verify that RS-MobCages is loaded.
You can also check the server console or run:

    /plugins

RS-MobCages should appear in the list of loaded plugins.

---

## First-Time Setup

Once RS-MobCages is installed, continue to:

➡️ [Getting Started](./docs/Getting-Started.md)

The Getting Started guide will walk through obtaining and using your first Mob Cage.

---

## Updating RS-MobCages

To update the plugin:

1. Stop the server.
2. Remove the old RS-MobCages `.jar` file from the `plugins` folder.
3. Place the new `.jar` file into the `plugins` folder.
4. Start the server.

Unless otherwise noted in the release notes, existing plugin data and configuration files should be preserved.
Always back up your server before performing updates.

---

## Troubleshooting Installation

If RS-MobCages does not appear in `/plugins`:

- Make sure the `.jar` file is inside the correct `plugins` folder.
- Check that you are using a supported Paper server version.
- Check the server console for plugin loading errors.
- Verify that your Java version is compatible with your Minecraft server.

For additional help, see:

➡️ [Troubleshooting](./docs/Troubleshooting.md)