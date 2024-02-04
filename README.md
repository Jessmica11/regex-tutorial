# Regex Guide: Unveiling the Hex Magic

Dive into the intricate world of URL validation with the regular expression `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`. This regex is your trusted guide to ensuring that URLs are structured correctly. Let's unravel the components that form this powerful URL-matching spell.

## Summary

Welcome to the coven, new web developer. We all want to learn the secrets behind the magical symbols of dev, and this tutorial will give you insights on hexadecimal codes for colors used amongst our digital spaces.

## Table of Contents

- [Intro](#introduction)
- [Decoding Components](#decoding-components)
  - [Securing the Protocol: ^(https?:\/\/)](#securing-the-protocol)
  - [Domain Dynamics: ([\da-z\.-]+)\.([a-z\.]{2,6})](#domain-dynamics)
  - [Navigating Paths: ([\/\w \.-]_)_](#navigating-paths)
- [Hex Value Decoding](#hex-value-decoding)
  - [Let Us Begin](#let-us-begin)
  - [Hex Spell](#hex-spell)
  - [Understanding Hexes](#understanding-hexes)

## Introduction

Imagine a world painted in hexadecimals, where colors are represented by mysterious codes. This regex tutorial is your [book of shadows](https://pluralism.org/book-shadows), guiding you on how to create a hex code (which may hex others into a vibrant web experience).

## Decoding Components

### Securing the Protocol: ^(https?:\/\/)

The regex begins with `^(https?:\/\/)`, ensuring the presence of an optional 'http://' or 'https://' protocol at the start of the URL.

**Example Journeys:**

- `https://www.example.com` (valid)
- `ftp://files.example.com` (invalid)

### Domain Dynamics: ([\da-z\.-]+)\.([a-z\.]{2,6})

This part of the regex focuses on capturing the domain, allowing alphanumeric characters, dots, and hyphens.

- **([\da-z\.-]+):** Matches the subdomain or domain name, ensuring it comprises alphanumeric characters, dots, and hyphens.

- **\.([a-z\.]{2,6}):** Enforces the presence of a dot followed by a top-level domain (TLD) with a length between 2 and 6 characters.

**Navigating Subdomains:**

- `blog.company.example` (valid)
- `http://123.45.67.89` (valid)

### Navigating Paths: ([\/\w \.-]_)_

This segment allows for the inclusion of paths, query parameters, and fragments in the URL.

- **([\/\w \.-]_)_:** Captures paths, allowing for a mix of forward slashes, alphanumeric characters, spaces, dots, and hyphens.

**Examples of the URL Journey:**

- `https://www.example.com/path/to/page` (valid)
- `https://www.example.com/page?param=value` (valid)

## Hex Value Decoding

### Let Us Begin

The regex starts with `^#?`, ensuring that the magic begins with an optional but welcomed '#' symbol, reminiscent of the enchanting color codes. It's important to keep your [grimoire](https://libguides.sdsu.edu/c.php?g=905875&p=6686265) close to your heart so it's used to its highest power, and magical symbolism and its rules must be followed.

**Example Incantations:**

- `#fa1f9c` (valid)
- `d3c45a` (invalid)

### Hex Spell

_~ [a-f0-9]{6}|[a-f0-9]{3} ~_

This segment is the core of the enchantment, accepting both the conventional and shorthand forms of Hex color codes.

- **[a-f0-9]{6}:** Unveils the power of long-form Hex color codes with precisely six characters. These six characters represent the intensity of Red, Green, and Blue (RGB) components in the color.

  **Spellbinding Instances:**

  - `#4d8cfa` (valid)
  - `#1a2b3c` (valid)

- **[a-f0-9]{3}:** Accepts the charm of short-form Hex color codes, featuring three characters for a quicker incantation. In this case, each character is duplicated to represent the RGB components.

  **Charming Examples:**

  - `#abc` (valid)
  - `#123` (valid)

### Understanding Hexes

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

Just a junior web dev [witch](https://github.com/Jessmica11) who has [Chromesthesia](https://pubmed.ncbi.nlm.nih.gov/2725872/).
