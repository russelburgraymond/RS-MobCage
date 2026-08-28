# Administrator Guide

This guide provides basic information for server administrators running RS-MobCages.

RS-MobCages is designed to require minimal administration and works with its default behavior after installation.

---

## Installation

Install RS-MobCages by placing the plugin `.jar` file into your server's:

    plugins/

folder.

Restart the server and verify that RS-MobCages loads successfully.

For detailed installation instructions, see:

➡️ [Installation](./docs/Installation.md)

---

## Server Administration

RS-MobCages currently does not require any special administrator setup.

There are currently:

- No required commands.
- No required permissions.
- No required configuration changes.

Once the plugin is installed and enabled, players can use Mob Cages to capture and release supported mobs.

---

## Supported Mobs

RS-MobCages only allows supported mobs to be captured.

The list of supported mobs may expand as additional mob descriptors are added to the plugin.

For the current list, see:

➡️ [Supported Mobs](./docs/Supported-Mobs.md)

---

## Named Mob Protection

Named mobs are protected from capture.

This helps prevent players from accidentally capturing mobs that have been intentionally named.

Server administrators should be aware of this behavior when testing or using Mob Cages.

---

## Plugin Updates

When updating RS-MobCages:

1. Stop the server.
2. Back up your server.
3. Remove the previous RS-MobCages `.jar` file.
4. Place the new `.jar` file into the `plugins` folder.
5. Start the server.
6. Check the console to confirm that the plugin loaded successfully.

Always review release notes when updating to a new version.

---

## Troubleshooting

If RS-MobCages does not appear to be working correctly:

- Verify that the plugin loaded successfully.
- Check the server console for errors.
- Confirm that the mob being tested is supported.
- Make sure the player is using an appropriate Mob Cage.
- Check that the mob does not have a custom name.

For additional troubleshooting information, see:

➡️ [Troubleshooting](./docs/Troubleshooting.md)