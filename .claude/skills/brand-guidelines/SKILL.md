---
name: brand-guidelines
description: Sablier brand guidelines including color palette (primary orange/blue gradients, dark theme, gray text colors), logo variations (square/wide, SVG/PNG formats), typography, icon assets, NFT designs, usage rules, and asset paths. Use when working with branding, design, colors, logos, icons, visual identity, or Sablier brand materials.
---

# Sablier Brand Guidelines

## Purpose

Comprehensive reference for Sablier brand identity including color system, logo variations, typography, and usage guidelines. Auto-activated when working with brand assets or asking about design specifications.

## When to Use

- Looking up brand colors (HEX codes, usage guidelines)
- Selecting appropriate logo/icon variations
- Understanding logo usage rules and restrictions
- Finding asset paths for development
- Designing NFT or Web3-specific materials
- Ensuring brand consistency across projects
- Working with design files (SVG, PNG, templates)

---

## Color Palette

### Primary Colors (Orange Gradient)

The signature Sablier gradient from vibrant orange to golden yellow:

- **Primary Start**: `#ff7300` - Vibrant orange (gradient start)
- **Primary End**: `#ffb800` - Golden yellow (gradient end)
- **Primary Middle**: `#ff9C00` - Median orange (gradient middle)

**Usage**: Main branding, CTAs, highlights, logo gradient

### Secondary Colors (Blue Gradient)

Complementary blue gradient for accents and variety:

- **Secondary Start**: `#003dff` - Deep blue (gradient start)
- **Secondary End**: `#00b7ff` - Cyan blue (gradient end)
- **Secondary Middle**: `#0063ff` - Medium blue (gradient middle)
- **Secondary Desaturated**: `#266cd9` - Muted blue (alternative)

**Usage**: Secondary CTAs, links, accents, alternative gradient

### Dark Palette (Dark Theme)

11-shade system for backgrounds, borders, and UI elements (primary theme):

| Color | HEX | Usage |
|-------|-----|-------|
| **Dark 000** | `#14161f` | Background - landing pages |
| **Dark 050** | `#1a1d28` | Background - deeper layers |
| **Dark 100** | `#1e212f` | Background - app default |
| **Dark 150** | `#212433` | Background - elevated |
| **Dark 200** | `#242838` | Background - higher elevation |
| **Dark 250** | `#262a3b` | Background - highest elevation |
| **Dark 300** | `#2a2e41` | Borders - cards, boxes |
| **Dark 400** | `#30354a` | Borders - inputs, interactive |
| **Dark 500** | `#363b54` | Borders - focus states |
| **Dark 600** | `#3c425d` | Subtle highlights |
| **Dark 700** | `#424966` | Mid-tone highlights |
| **Dark 800** | `#484f70` | Light highlights |
| **Dark 900** | `#4e5679` | Lighter highlights |
| **Dark 1000** | `#545c82` | Lightest highlights |

**Notes**:
- Shades created by increasing lightness of Dark 000
- Noise applied to gradients to reduce banding
- **Never use pure black** (`#000000`)

### Gray Palette (Text & Labels)

5-shade system for typography and labels:

- **Gray 100**: `#e1e4ea` - Primary text color
- **Gray 200**: `#c3c9d5` - Secondary text color
- **Gray 300**: `#a5aec0` - Tertiary text
- **Gray 400**: `#8792ab` - Labels, subtle text
- **Gray 500**: `#6a7795` - Muted labels

**Usage**:
- Long-form text: Gray 100-200 (not pure white)
- Labels/metadata: Gray 400-500
- Never use pure white for body text

### Accent Colors

- **Red**: `#e52e52` - Errors, warnings, alerts, destructive actions

### Color Guidelines

✅ **Do**:
- Use primary gradient for main branding
- Apply noise overlay to prevent banding
- Use gray palette for readable text
- Follow dark theme specifications

❌ **Don't**:
- Use pure black (#000000)
- Use pure white (#ffffff) for body text
- Mix gradients inappropriately
- Ignore accessibility contrast ratios

---

## Logo Guidelines

### Logo Variations

#### Wide Format
**Location**: `/logo/wide/`

| Variation | Format | Use Case |
|-----------|--------|----------|
| `all-gradient` | SVG, PNG | Light backgrounds, full color |
| `all-black` | SVG, PNG | Light backgrounds, monochrome |
| `all-white` | SVG, PNG | Dark backgrounds, monochrome |
| `all-dark` | SVG, PNG | Light backgrounds, dark variant |
| `gradient-black` | SVG, PNG | Primary brand (orange gradient + black text) |
| `gradient-white` | SVG, PNG | Dark backgrounds (orange gradient + white text) |
| `solid-wide-orange-black` | PNG | Solid orange + black text |

#### Square Format
**Location**: `/logo/square/`

| Variation | Format | Use Case |
|-----------|--------|----------|
| `gradient` | SVG, PNG | Full color icon |
| `black` | SVG, PNG | Light backgrounds |
| `black-solid` | PNG | Light backgrounds, solid treatment |
| `solid` | PNG | Solid color icon |
| `dark` | SVG | Dark variant |

### Icon Assets

**Location**: `/icon/`

**Standard Sizes**: 192px, 250px, 256px, 1024px, 1500px
**Special Variants**:
- `icon-padding-*.png` - With spacing for tight layouts
- `icon-white-background.png` - For print/light contexts
- `icon-black.png` - Monochrome variant
- `icon-solid.png` - Solid color treatment
- `favicon/favicon.ico` - Browser favicon

**Contextual Icons** (`/other/`):
- `stream-circle-streaming.png` - Active stream indicator
- `stream-circle-ended.png` - Ended stream indicator
- `icon-subgraph-primary.png` - Subgraph branding (primary)
- `icon-subgraph-secondary.png` - Subgraph branding (secondary)

### Print-Ready Assets

**Location**: `/print/`

Professional print files with Pantone specifications:
- **Formats**: PSD (editable), PDF (camera-ready), PNG (high-res)
- **Contents**: Logo and icon in Pantone colors
- **Backgrounds**: White, black, transparent variants
- **Use**: Professional printing, merchandise, signage

### Usage Rules

✅ **Do**:
- Use appropriate format (SVG for web scaling, PNG for specific sizes)
- Maintain minimum clear space around logo
- Use correct variation for background (light/dark)
- Preserve gradient colors when using color versions

❌ **Don't**:
- Edit, modify, distort, or rotate the logo
- Recolor the logo outside approved variations
- Combine with other logos (except pre-approved partnerships)
- Stretch or skew proportions
- Place on busy backgrounds without sufficient contrast

---

## Typography

### Current State

**Wordmark Font**: Custom sans-serif embedded in logo files
- Modern, clean geometric sans-serif
- No separate font files in repository
- Typography is integral to logo SVG/PNG files

**Status**: No separate typography documentation exists yet

**Recommendation**: For body text/UI, use standard system fonts or web-safe alternatives:
- **Sans-serif**: Inter, SF Pro, Segoe UI, Roboto
- **Monospace**: JetBrains Mono, Fira Code, Monaco

---

## NFT Guidelines

### Sablier V2 Hourglass NFT

**Location**: `/nft/`

**Variations**:
- `nft-green.png` - Green theme
- `nft-purple.png` - Purple theme
- `nft-red.png` - Red theme
- `nft-white.png` - White/light theme
- `nft-hourglass.png` - Standard hourglass design
- `nft-hourglass-art.png` - Artistic variant

**Design Elements**:
- Hourglass icon with gradient treatment
- Dynamic color variations for different stream states
- Web3-native aesthetic
- Suitable for on-chain display and marketplaces

---

## Templates & Marketing

**Location**: `/template/`

**Banner Templates**:
- `banner.png` - Standard promotional banner
- `banner-branding.png` - Brand showcase banner
- `banner-colors.png` - Color palette showcase
- `banner-nft.png` - NFT-focused banner

**Partnership Materials**:
- `partnership.png` - Partnership template
- `partnership-example.png` - Example application

**Video**:
- `youtube-cover.png` - Video thumbnail template

---

## Quick Asset Lookup

### For Developers

**Dark Theme App (Default)**:
```
Background: #1e212f (Dark 100)
Borders: #2a2e41 (Dark 300) for cards, #30354a (Dark 400) for inputs
Text: #e1e4ea (Gray 100) primary, #c3c9d5 (Gray 200) secondary
Labels: #8792ab (Gray 400)
Primary CTA: Linear gradient from #ff7300 to #ffb800
```

**Logo Integration**:
```html
<!-- Light background -->
<img src="/logo/wide/all-gradient.svg" alt="Sablier" />

<!-- Dark background -->
<img src="/logo/wide/gradient-white.svg" alt="Sablier" />

<!-- Icon only -->
<img src="/icon/svg/icon.svg" alt="Sablier" width="256" />
```

### For Designers

**Primary Gradient CSS**:
```css
background: linear-gradient(135deg, #ff7300 0%, #ffb800 100%);
```

**Secondary Gradient CSS**:
```css
background: linear-gradient(135deg, #003dff 0%, #00b7ff 100%);
```

**Noise Overlay** (to prevent banding):
Apply subtle noise texture over gradients for smoother visual quality.

---

## File Structure Reference

```
branding/
├── icon/               # Icon assets (SVG, PNG, favicon)
│   ├── svg/           # Vector icon
│   ├── png/           # Raster icons (192px-1500px)
│   └── favicon/       # Browser favicon
├── logo/              # Logo variations
│   ├── square/        # Square format (dark, gradient, solid)
│   └── wide/          # Wide format (all-*, gradient-*, solid)
├── nft/               # NFT design examples (Hourglass variations)
├── other/             # Contextual icons (stream status, subgraph)
├── print/             # Print-ready files (PSD, PDF, Pantone)
├── template/          # Banners and partnership templates
└── README.md          # Comprehensive brand documentation
```

---

## Brand Voice & Principles

### Visual Principles

1. **Gradient-First**: Orange-to-yellow gradient is signature element
2. **Dark Theme Native**: Designed primarily for dark interfaces (V2+)
3. **Clean & Modern**: Geometric, minimal, professional
4. **Web3-Native**: Designed for blockchain/DeFi context
5. **Accessible**: Sufficient contrast, readable text colors

### Color Philosophy

- **Vibrant & Warm**: Orange gradient conveys energy and time
- **Trustworthy**: Blue accents provide balance and professionalism
- **Sophisticated**: Dark theme with subtle gradations
- **Never Harsh**: No pure black, noise applied to smooth gradients

### Logo Philosophy

- **Iconic Hourglass**: Represents time streaming
- **Standalone Strength**: Icon works independently
- **Versatile**: Multiple variations for different contexts
- **Scalable**: Vector-first for any size

---

## Accessibility Notes

**Color Contrast**:
- Gray 100 on Dark 100: ✅ Passes WCAG AA
- Gray 200 on Dark 100: ✅ Passes WCAG AA
- Gray 400 on Dark 100: ⚠️ Use for labels only, not body text
- Orange gradient on Dark 100: ✅ High contrast

**Recommendations**:
- Always test color combinations
- Use Gray 100-200 for readable text
- Ensure sufficient contrast for interactive elements
- Provide text alternatives for color-coded information

---

## Support & Resources

**Full Documentation**: See `/README.md` in branding repository

**Visual Examples**: All logo and icon variations include PNG previews

**Need Help?**:
- Review `/README.md` for comprehensive guidelines
- Check `/template/` for usage examples
- Examine NFT examples for Web3-specific applications

---

**Skill Version**: 1.0.0
**Last Updated**: 2025-11-05
**Repository**: `/Users/prb/sablier/branding`
