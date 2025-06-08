# StatoGasm Typography & Font Style Guide

## ✨ Brand Personality

**Powerful. Retro. Explosive. Precision-Driven.**

* The typography reflects statistical intensity with athletic boldness.
* Built for visual impact, digital clarity, and sports-data nostalgia.

---

## 🔠 Type Styles Reference

### H1 – Main Title

```css
font-family: 'Bebas Neue', 'Anton', sans-serif;
font-weight: 900;
font-size: 3.5rem;
letter-spacing: 0.05em;
text-transform: uppercase;
```

* Used for primary page or section headers

### H2 – Section Header

```css
font-family: 'Bebas Neue', 'Anton';
font-weight: 700;
font-size: 2.5rem;
letter-spacing: 0.03em;
text-transform: uppercase;
```

### H3 – Subsection Title

```css
font-family: 'Anton', 'Graduate';
font-weight: 600;
font-size: 1.75rem;
text-transform: uppercase;
```

### Body 1 – Primary Paragraph Text

```css
font-family: 'Inter', 'Barlow';
font-weight: 400;
font-size: 1.125rem;
line-height: 1.6;
color: #AAA69D;
```

### Body 2 – Secondary Text

```css
font-family: 'Roboto', 'Barlow';
font-weight: 300;
font-size: 0.95rem;
line-height: 1.6;
color: #999999;
```

### Caption

```css
font-family: 'Inter';
font-weight: 300;
font-size: 0.75rem;
color: #777777;
letter-spacing: 0.05em;
text-transform: uppercase;
```

* Used for stat notes, player notes, chart footnotes

### Code (Monospace)

```css
font-family: 'Fira Code', 'Source Code Pro';
font-size: 0.9rem;
background-color: #2A1B10;
color: #F9B233;
padding: 0.5em;
border-radius: 4px;
```

* For formulas, scripts, CLI, and stat overlays

### Header/Footer Styles

**Header**

```css
font-family: 'Anton';
font-size: 1.2rem;
font-weight: 600;
text-transform: uppercase;
color: #F9B233;
```

**Footer**

```css
font-family: 'Inter';
font-size: 0.8rem;
font-weight: 300;
color: #5E2D0C;
letter-spacing: 0.03em;
```

* Include page number, site address, copyright

---

## 🔐 Logo Typography

### Characteristics:

* **Case**: ALL CAPS ONLY
* **Weight**: Ultra Bold (900+)
* **Style**: Block Serif / Slab Sans
* **Shape**: Angular, beveled, arcade-style edges
* **Effects**: Subtle shadowing, gradients, inner glow

### Font Options:

* `Bebas Neue Pro`
* `Anton`
* `Graduate`
* `Racing Sans One`
* `Staatliches`

### Stacking Convention:

```txt
STATO
GASM
```

* Used for icons and brand-heavy content

### Inline Version:

```txt
STATOGASM
```

* For web navs, footers, or meta branding

---

## 📘 Web & Docs Typography

### Headings (H1 - H3):

```css
font-family: 'Bebas Neue', 'Anton', Impact, sans-serif;
font-weight: 700;
letter-spacing: 0.05em;
text-transform: uppercase;
```

* Use for titles, data dashboards, leaderboard sections

### Body Text:

```css
font-family: 'Inter', 'Barlow', 'Roboto', sans-serif;
font-weight: 400;
line-height: 1.6;
color: #AAA69D;
```

* Use for labels, stats text, metadata

### Monospace (Data, Code):

```css
font-family: 'Fira Code', 'Source Code Pro', monospace;
background-color: #2A1B10;
padding: 0.5em;
border-radius: 4px;
```

* Use in stat models, logs, formula docs

---

## 🎨 Font Color Roles

| Use Case    | Weight  | Color        | Hex       |
| ----------- | ------- | ------------ | --------- |
| Headers     | Bold    | Inferno Gold | `#F9B233` |
| Accents     | Medium  | Blaze Orange | `#E85B0D` |
| Body Text   | Regular | Ash Gray     | `#AAA69D` |
| Meta/Labels | Light   | Burnt Umber  | `#5E2D0C` |

---

## ⚖️ Font Pairings

| Context             | Heading Font      | Body Font |
| ------------------- | ----------------- | --------- |
| Web UI / Dashboards | Bebas Neue        | Inter     |
| Poster / Print      | Anton or Graduate | Barlow    |
| Reports / Docs      | Staatliches       | Roboto    |
| Code / Data Display | Anton             | Fira Code |

---

## 🔧 Implementation Notes

* **Use SVG or Outline Text for Logos**: Avoid font loading issues.
* **Google Fonts CDN**:

```html
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
```

* **Export fallback web-safe stack:**

```css
font-family: 'Bebas Neue', Impact, Arial, sans-serif;
```

---

## 🎉 Usage Examples

* `STATO\nGASM` stacked inside explosion emblem = Brand Icon
* `STATOGASM` inline in nav bar = Header Branding
* `#AAA69D` Inter font = Stat notes or metadata in dashboards
* `Fira Code` = For formula overlays or scripts in StatalyticS

---

## 📄 Version

* **Created:** June 8, 2025
* **Author:** xSTATx | Branding: StatoGasm bySTRIK3
