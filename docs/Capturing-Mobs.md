# Capturing Mobs

This guide explains how to capture mobs using RS-MobCages.

Mob Cages allow supported mobs to be captured and stored inside a portable cage for transportation.

---

## Before Capturing a Mob

Before attempting to capture a mob, make sure you have:

- An empty Mob Cage.
- The Mob Cage in your main hand.
- A supported mob to capture.

Not every entity can be captured.

Players cannot be captured, and named mobs are protected from accidental capture.

For a complete list of supported mobs, see:

➡️ [Supported Mobs](./docs/Supported-Mobs.md)

---

## Capturing a Mob

To capture a mob:

1. Place an empty Mob Cage in your main hand.
2. Approach a supported mob.
3. Use the Mob Cage on the mob.

If the mob can be captured, the capture will be processed.

The mob will be removed from the world and the empty Mob Cage will become a filled Mob Cage containing that mob.

---

## Successful Capture

When a mob is successfully captured:

- The original mob is removed from the world.
- The Mob Cage becomes associated with the captured mob.
- The filled cage can be carried in a player's inventory.
- Mob-specific information is stored when supported by the mob's descriptor.

The filled Mob Cage can then be transported and released at another location.

See:

➡️ [Releasing Mobs](./docs/Releasing-Mobs.md)

---

## Named Mobs

RS-MobCages protects named mobs from being accidentally captured.

If a mob has a custom name, it cannot be captured.

This helps prevent players from accidentally placing important, decorative, or specially named mobs into a Mob Cage.

---

## Players

Players cannot be captured.

Mob Cages are intended for supported mobs only.

---

## Unsupported Mobs

If you attempt to capture an unsupported entity, the capture will not be completed.

RS-MobCages only captures mobs that are supported by the plugin.

For the complete list, see:

➡️ [Supported Mobs](./docs/Supported-Mobs.md)

---

## After Capturing

Once a mob has been captured, the filled Mob Cage can be:

- Carried in your inventory.
- Moved to another location.
- Stored until needed.
- Released when you are ready to place the mob.

To learn how to release a captured mob, continue to:

➡️ [Releasing Mobs](./docs/Releasing-Mobs.md)