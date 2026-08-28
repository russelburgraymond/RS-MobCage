# Mob Variants and Attributes

Some mobs have different appearances, variants, or attributes that make them different from the standard version of that mob.

RS-MobCages can store mob-specific information so that supported mobs can be released with the appropriate appearance or variant.

The exact information stored depends on the mob and its support within RS-MobCages.

---

## Why Variants Matter

Many Minecraft mobs are not visually identical.

For example, two sheep may both be sheep, but they may have different wool colors.

Other mobs may have different:

- Colors
- Variants
- Types
- Patterns
- Appearances
- Mob-specific attributes

When supported, RS-MobCages stores this information when the mob is captured and applies it again when the mob is released.

---

## Examples

Depending on the supported mob, this may include information such as:

### Sheep

Sheep may have different wool colors.

A captured sheep can retain its supported wool color information when released.

---

### Cats

Cats can have different variants and appearances.

When supported, the captured cat's variant information can be stored and restored.

---

### Horses and Other Equines

Horses and other equine mobs may have appearance or variant information that differs between individual mobs.

Supported information can be stored as part of the captured mob's data.

---

### Other Variant Mobs

Other supported mobs may also have their own descriptors for handling mob-specific information.

As RS-MobCages expands, additional mobs and their supported attributes may be added.

---

## Attribute Support

Not every property of a mob is necessarily stored.

Support depends on the specific mob descriptor and the information currently implemented for that mob.

For example, a supported mob may preserve:

- Its variant
- Its color
- Its appearance
- Other supported mob-specific information

Other properties may not currently be preserved.

---

## Future Mob Support

RS-MobCages is designed to allow additional mob types and mob-specific attributes to be added over time.

As new mobs are added, their descriptors can define which information should be stored and restored.

This allows the plugin to expand without requiring every mob to use the exact same capture and release logic.

---

## Important Notes

Mob-specific support may change as RS-MobCages develops.

The [Supported Mobs](./docs/Supported-Mobs.md) page will be updated as additional mobs are added.

If a particular mob has special handling or limitations, those details should be documented with that mob's supported behavior.
