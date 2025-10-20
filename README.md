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

![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) `#FFA500`  

```scss
// Set the case color in your variables
$clr--base: #FFA500;
```

### Brand Color Palette

![#FFF1CC](https://placehold.co/15x15/FFF1CC/FFF1CC.png) `--clr-base-10`  
![#FFE199](https://placehold.co/15x15/FFE199/FFE199.png) `--clr-base-20`  
![#FFD066](https://placehold.co/15x15/FFD066/FFD066.png) `--clr-base-30`  
![#FFBF33](https://placehold.co/15x15/FFBF33/FFBF33.png) `--clr-base-40`  
![#FFAA00](https://placehold.co/15x15/FFAA00/FFAA00.png) `--clr-base-50`  
![#E69400](https://placehold.co/15x15/E69400/E69400.png) `--clr-base-60`  
![#CC7F00](https://placehold.co/15x15/CC7F00/CC7F00.png) `--clr-base-70`  
![#B36600](https://placehold.co/15x15/B36600/B36600.png) `--clr-base-80`  
![#994D00](https://placehold.co/15x15/994D00/994D00.png) `--clr-base-90`  
![#803300](https://placehold.co/15x15/803300/803300.png) `--clr-base-100`



```scss
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