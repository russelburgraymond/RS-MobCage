# Troubleshooting

This guide covers common issues you may encounter while using RS-MobCages.

---

## The Plugin Does Not Appear in `/plugins`

If RS-MobCages does not appear in the `/plugins` list:

1. Verify that the RS-MobCages `.jar` file is located in your server's:

        plugins/

   folder.

2. Restart the server.

3. Check the server console for errors related to RS-MobCages.

4. Make sure you are using a supported Paper server version.

If the plugin reports an error during startup, review the full error message in the server console.

---

## I Cannot Capture a Mob

If a mob cannot be captured, check the following:

- Make sure you are holding an empty Mob Cage.
- Make sure the mob is supported by RS-MobCages.
- Make sure the mob does not have a custom name.
- Make sure you are interacting directly with the mob.

Not every entity can be captured.

For the current list of supported mobs, see:

➡️ [Supported Mobs](./docs/Supported-Mobs.md)

---

## I Cannot Capture a Named Mob

This is expected behavior.

RS-MobCages prevents named mobs from being captured.

A mob with a custom name is protected from accidental capture.

If the mob is intentionally named, remove the custom name before attempting to capture it.

---

## I Cannot Capture a Player

Players cannot be captured.

Mob Cages are intended for supported mobs only.

---

## The Mob I Am Trying to Capture Is Not Supported

RS-MobCages only captures mobs that are currently supported by the plugin.

If a mob is not listed on the [Supported Mobs](./docs/Supported-Mobs.md) page, it cannot currently be captured.

Additional mob support may be added in future updates.

---

## The Mob Will Not Release

If a captured mob does not release as expected:

- Make sure you are using a filled Mob Cage.
- Make sure there is enough open space for the mob to appear.
- Try moving to a different location.
- Make sure the area is not blocked by solid blocks.

If the problem continues, check the server console for any errors.

---

## The Mob Does Not Look the Same After Release

Some mobs have variants, colors, or other unique attributes.

RS-MobCages can preserve supported mob-specific information, but not every possible property is necessarily stored.

For more information, see:

➡️ [Mob Variants and Attributes](./docs/Mob-Variants-and-Attributes.md)

---

## The Plugin Stops Working After an Update

If RS-MobCages worked previously but stops working after an update:

1. Stop the server.
2. Check that only one version of `RS-MobCages.jar` is installed.
3. Verify that you are using the correct version of the plugin for your server.
4. Check the server console for errors.
5. Review the release notes for the version you installed.

Always back up your server before updating plugins.

---

## Reporting a Bug

If you believe you have found a bug, please include as much information as possible when reporting it.

Helpful information includes:

- Minecraft version
- Paper version
- RS-MobCages version
- What you were doing when the problem occurred
- Which mob was involved
- Any relevant server console errors

Clear reproduction steps make bugs much easier to identify and fix.
