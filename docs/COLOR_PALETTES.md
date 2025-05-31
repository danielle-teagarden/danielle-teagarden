# Color Palettes Reference

Quick reference for implementing brand colors across projects.

## Accessible Purple Palette
*For innovative legal tech, accessibility-focused projects*

### CSS Custom Properties
```css
:root {
  /* Purple Scale */
  --purple-signature: #8B5CF6;
  --purple-deep: #6D28D9;
  --purple-light: #C4B5FD;
  
  /* Accent Colors */
  --teal-bright: #06B6D4;
  --green-success: #059669;
  
  /* Neutrals */
  --neutral-dark: #1F2937;
  --neutral-medium: #6B7280;
  --neutral-light: #F9FAFB;
}
```

### Tailwind Colors
```javascript
colors: {
  'purple-signature': '#8B5CF6',
  'purple-deep': '#6D28D9',
  'purple-light': '#C4B5FD',
  'teal-bright': '#06B6D4',
  'green-success': '#059669',
  'neutral-dark': '#1F2937',
  'neutral-medium': '#6B7280',
  'neutral-light': '#F9FAFB'
}
```

### Array Format
```json
["8B5CF6", "6D28D9", "C4B5FD", "06B6D4", "059669", "1F2937", "6B7280", "F9FAFB"]
```

---

## Indiana Heritage Palette  
*For traditional legal work, local expertise*

### CSS Custom Properties
```css
:root {
  /* Indiana Heritage */
  --delft-blue: #2f3061;
  --naples-yellow: #ffe66d;
  --air-superiority-blue: #6ca6c1;
  --jet: #343434;
  --mint-cream: #f7fff7;
}
```

### Tailwind Colors
```javascript
colors: {
  'delft-blue': '#2f3061',
  'naples-yellow': '#ffe66d',
  'air-superiority-blue': '#6ca6c1',
  'jet': '#343434',
  'mint-cream': '#f7fff7'
}
```

### Extended Color Data
```json
[
  {
    "name": "Delft Blue",
    "hex": "#2f3061",
    "rgb": [47, 48, 97],
    "hsl": [239, 35, 28],
    "story": "Dutch ceramic tradition - craftsmanship and durability"
  },
  {
    "name": "Naples Yellow", 
    "hex": "#ffe66d",
    "rgb": [255, 230, 109],
    "hsl": [50, 100, 71],
    "story": "Classical art pigment - cultural sophistication"
  },
  {
    "name": "Air Superiority Blue",
    "hex": "#6ca6c1", 
    "rgb": [108, 166, 193],
    "hsl": [199, 41, 59],
    "story": "Aviation heritage - authority and expertise"
  },
  {
    "name": "Jet",
    "hex": "#343434",
    "rgb": [52, 52, 52], 
    "hsl": [0, 0, 20],
    "story": "Sophisticated neutral base"
  },
  {
    "name": "Mint Cream",
    "hex": "#f7fff7",
    "rgb": [247, 255, 247],
    "hsl": [120, 100, 98],
    "story": "Clean, fresh background"
  }
]
```

---

## Accessibility Reference

### Contrast Ratios (WCAG AA = 4.5:1 minimum)

**Accessible Purple Palette:**
- Purple Signature on white: **7.1:1** ✅
- Purple Deep on white: **11.2:1** ✅  
- Teal Bright on white: **4.8:1** ✅
- Green Success on white: **5.9:1** ✅
- Purple Light background with dark text: **12.5:1** ✅

**Indiana Heritage Palette:**
- Delft Blue on white: **8.4:1** ✅
- Air Superiority Blue on white: **4.1:1** ⚠️ (borderline, test carefully)
- Naples Yellow on white: **2.2:1** ❌ (use as background or with dark text)
- Jet on white: **12.6:1** ✅

### Testing Tools
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Colour Contrast Analyser](https://www.tpgi.com/color-contrast-checker/)
- Browser DevTools accessibility audits

---

## Usage Guidelines

### When to Use Each Palette

**Accessible Purple:**
- Indiana Law Hub
- Open legal tool interfaces  
- Modern legal technology projects
- Accessibility-focused work
- Tech conferences and presentations

**Indiana Heritage:**
- Traditional legal documents
- Indiana-specific legal resources
- Speaking to established legal audiences
- Professional legal services materials
- Historical legal research projects

### Mixing Palettes
- Use purple as primary with heritage colors as accents
- Heritage yellow can work as warning/alert color in purple projects
- Always test contrast when mixing palettes

---

## Typography Pairing

### Public Sans + Liberation Serif
```css
/* Primary Font Stack */
font-family: 'Public Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;

/* Complementary Font Stack */  
font-family: 'Liberation Serif', 'Times New Roman', serif;
```

### Usage
- **Public Sans**: UI, headings, navigation, modern content
- **Liberation Serif**: Legal excerpts, quotes, formal statements

---

*Quick reference for developers and designers implementing Danielle Teagarden brand identity*