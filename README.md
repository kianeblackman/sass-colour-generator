# 🎨 SCSS Color Generator

A lightweight **SCSS color generation tool** that produces a smooth 10-step color palette from a single base color.  
Perfect for quickling styling websites with a range of colors on the fly.

---

## 🌈 Features

- Generate 10 shades from a single base color (`--clr-10` → `--clr-100`)
- Automatically adjusts lightness/darkness evenly
- Perfect for use in component-based systems (React, Vue, etc.)
- No dependencies — 100% pure SCSS

---

## 🖍️ Example

### Brand Base Color

<div style="text-align:left;">
  <div style="background-color:orange; width:40px; height:40px; border-radius:4px;"></div>
  <span>base</span>
</div>

```scss
// Set the case color in your variables
$clr--base: #FFA500;
```

### Brand Color Palette

<div style="display:flex; gap:5px; align-items:flex-end;">
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 82%); width:40px; height:40px; border-radius:4px;"></div>
    <span>10</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 74%); width:40px; height:40px; border-radius:4px;"></div>
    <span>20</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 66%); width:40px; height:40px; border-radius:4px;"></div>
    <span>30</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 58%); width:40px; height:40px; border-radius:4px;"></div>
    <span>40</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 50%); width:40px; height:40px; border-radius:4px;"></div>
    <span>50</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 42%); width:40px; height:40px; border-radius:4px;"></div>
    <span>60</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 34%); width:40px; height:40px; border-radius:4px;"></div>
    <span>70</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 26%); width:40px; height:40px; border-radius:4px;"></div>
    <span>80</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 18%); width:40px; height:40px; border-radius:4px;"></div>
    <span>90</span>
  </div>
  <div style="text-align:center;">
    <div style="background-color:hsl(38.8235294118, 100%, 10%); width:40px; height:40px; border-radius:4px;"></div>
    <span>100</span>
  </div>
</div>

```css
// CSS variables output

--clr-base-10: hsl(38.8235294118, 100%, 82%);
--clr-base-20: hsl(38.8235294118, 100%, 74%);
--clr-base-30: hsl(38.8235294118, 100%, 66%);
--clr-base-40: hsl(38.8235294118, 100%, 58%);
--clr-base-50: hsl(38.8235294118, 100%, 50%);
--clr-base-60: hsl(38.8235294118, 100%, 42%);
--clr-base-70: hsl(38.8235294118, 100%, 34%);
--clr-base-80: hsl(38.8235294118, 100%, 26%);
--clr-base-90: hsl(38.8235294118, 100%, 18%);
--clr-base-100: hsl(38.8235294118, 100%, 10%)
```