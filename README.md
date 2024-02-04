# Regex Guide: Unveiling the Hex Magic

## Summary

Welcome to the coven, new web developer. Explore the the secrets of arcane patterns within strings through the art of regular expressions (regex). This tutorial unveils the hidden powers of a specific regex, known as the Hex Code, crafted to match the enchanting hex values. We all want to learn the secrets behind the magical symbols of dev, and this tutorial will give you insights on hexadecimal codes for colors used amongst our digital spaces.

## Table of Contents

1. [Hex Spell Overview](#hex-spell-overview)
2. [Magical Components](#magical-components)
   - [Component 1: `^`](#component-1)
   - [Component 2: `#`](#component-2)
   - [Component 3: `([a-fA-F0-9]{6}|[a-fA-F0-9]{3})`](#component-3)
   - [Component 4: `$`](#component-4)
3. [Understanding Hexes](#understanding-hexes)
4. [Conclusion](#conclusion)
5. [Author](#author)

## Hex Spell Overview

```regex
/^#([a-fA-F0-9]{6}|[a-fA-F0-9]{3})$/
```

## Magical Components

### Component 1

The regex starts with a caret (^) for initiation.

### Component 2

The optional but welcomed '#' symbol, reminiscent of the enchanting color codes.

**Example Incantations:**

- `#fa1f9c` (valid)
- `d3c45a` (invalid)

### Component 3

```
([a-fA-F0-9]{6}|[a-fA-F0-9]{3})
```

This enchanted component harbors the very essence of the hex magic. It comprises two mystical alternatives separated by a magical pipe (|) symbol, allowing for either a 6-character or 3-character hex code.

`[a-fA-F0-9]{6}`: Conjures a 6-character hex value, where each character embodies the spirit of a valid hexadecimal digit (0-9, a-f, A-F).

`[a-fA-F0-9]{3}`: Summons a 3-character hex value, adhering to the same magical rules as its 6-character counterpart.

The dollar sign ($), a magical seal, asserts the end of the string. It ensures that the hex concludes at the very end.

**Spellbinding Instances:**

- `#4d8cfa` (valid)
- `#1a2b3c` (valid)

- **[a-f0-9]{3}:** Accepts the charm of short-form Hex color codes, featuring three characters for a quicker incantation. In this case, each character is duplicated to represent the Red, Green, Blue (RGB) color components.

  **Charming Examples:**

  - `#abc` (valid)
  - `#123` (valid)

### Component 4

The dollar sign `$`, a magical seal, asserts the end of the string. It ensures that the hex magic concludes at the very end.

It's important to keep your [grimoire](https://libguides.sdsu.edu/c.php?g=905875&p=6686265) close to your heart so it's used to its highest power, and magical symbolism and its rules must be followed.

## Understanding Hexes

Hexadecimal is a base-16 number system, using digits 0-9 and letters A-F to represent values from 0 to 15. In the context of Hex color codes:

- The first two characters represent the Red component.
- The next two characters represent the Green component.
- The final two characters represent the Blue component.

For example, in the Hex code `#4d8cfa`:

- `4d` represents the Red component.
- `8c` represents the Green component.
- `fa` represents the Blue component.

Understanding this structure allows you to visualize and manipulate colors effectively in web design.

Red, Green, and Blue are the primary colors of light. In digital color representation:

- Red (R): Determines the intensity of the red color in the overall shade.
- Green (G): Controls the intensity of the green color in the mix.
- Blue (B): Governs the intensity of the blue color.

Each component can take values from 0 to 255, where 0 indicates no intensity, and 255 indicates full intensity. The combination of these three components in varying intensities results in a vast spectrum of colors.

For instance, in the RGB components of `#4d8cfa`:

- Red (R): 77 (decimal equivalent of `4d`)
- Green (G): 140 (decimal equivalent of `8c`)
- Blue (B): 250 (decimal equivalent of `fa`)

Understanding RGB
Understanding RGB components empowers you to fine-tune colors to achieve the desired visual effects.

All symbols have meanings, similar to how other spellbooks use [runes](https://runicstudies.org/) or [sigil work](https://www.collegeofpsychicstudies.co.uk/enlighten/how-to-make-a-sigil/) to convey meaning and create properties.

## Conclusion

Congratulations, you've mastered the art of deciphering Hex color codes using the spellbinding regex `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`. As you venture into the realm of web design, may your colors be vibrant, your codes be true, and your understanding of Hexadecimal magic be ever-expanding.

🔮 _Sky Above, Earth Below, Fire Within_ 🔮

## Author

Just a junior web dev [witch](https://github.com/Jessmica11) who has [Chromesthesia](https://pubmed.ncbi.nlm.nih.gov/29259260/).

![Figure-2 from "Musical pitch classes have rainbow hues in pitch class-color synesthesia"](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41598-017-18150-y/MediaObjects/41598_2017_18150_Fig2_HTML.jpg?as=webp)
[Figure-2 from "Musical pitch classes have rainbow hues in pitch class-color synesthesia"](https://www.nature.com/articles/s41598-017-18150-y)
