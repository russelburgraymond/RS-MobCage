# Supported Mobs

This page lists the mobs that can be captured using RS-MobCages.

RS-MobCages uses individual mob descriptors to determine how supported mobs are captured and released.

Each supported mob may have its own handling for variants, appearance, or other mob-specific information.

---

## Supported Mobs

RS-MobCages supports the following mobs:

### Passive Mobs

- Cow
- Chicken
- Goat
- Pig
- Sheep
- Rabbit
- Horse
- Donkey

### Cats and Wolves

- Cat

### Other Passive Mobs

- Bee
- Parrot

### Villagers

- Villager

### Hostile Mobs

- Slime
- Magma Cube
- Zombie
- Spider
- Skeleton
- Cave Spider

---

## Mob Variants

Some mobs have multiple possible appearances or variants.

When supported by the mob's descriptor, RS-MobCages stores the information necessary to recreate that variant when the mob is released.

Examples may include:

- Sheep wool color
- Cat variants
- Wolf variants
- Horse appearance
- Rabbit variants
- Frog variants
- Parrot variants
- Axolotl variants
- Tropical fish appearance

For more information, see:

➡️ [Mob Variants and Attributes](./docs/Mob-Variants-and-Attributes.md)

---

## Named Mobs

Named mobs cannot be captured.

If a mob has been given a custom name, RS-MobCages will prevent it from being captured.

This helps protect:

- Pets
- Decorative mobs
- Named villagers
- Important server mobs
- Other mobs that players have intentionally named

---

## Unsupported Mobs

If a mob is not supported by RS-MobCages, it cannot be captured.

The plugin will safely ignore unsupported entities.

Players cannot be captured.

---

## Important Notes

Support for a mob does not necessarily mean that every possible property of that mob is stored.

Mob-specific information is handled individually by the mob's descriptor.

Some mobs may preserve variants or appearance information, while others may only require their basic entity type to be stored.
