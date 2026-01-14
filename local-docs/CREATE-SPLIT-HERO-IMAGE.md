# Create Split-Face Hero Image - Step-by-Step Guide

## What We're Creating

**Designer | Developer** split portrait:
- **LEFT half:** Watercolor/artistic (your existing image)
- **RIGHT half:** Code/typography overlay
- **Result:** Unique visual showing your dual skills

---

## What You Need

✅ Your watercolor image (already have it!)  
✅ Figma (free account works)  
✅ 30-45 minutes

---

## STEP-BY-STEP INSTRUCTIONS

### Step 1: Set Up Figma Canvas (2 minutes)

1. **Open Figma** (figma.com)
2. **Create new file:** Click "New design file"
3. **Create frame:**
   - Press `F` (frame tool)
   - Click and drag
   - In right panel, set size:
     - Width: **1000px**
     - Height: **1200px**
   - Name it: "Hero Image"

---

### Step 2: Import Your Image (1 minute)

1. **Import watercolor image:**
   - Drag and drop: `718DB44F-7A31-417A-85D9-F241A7B822A1.PNG`
   - Or: File → Place image
2. **Scale to fit frame:**
   - Click image
   - Right panel → Constraints → Scale
   - Resize to fill 1000×1200px frame
   - Center it

---

### Step 3: Duplicate Image Layer (1 minute)

1. **Select image layer**
2. **Duplicate:** 
   - Mac: `Cmd + D`
   - Windows: `Ctrl + D`
3. **You now have 2 identical layers**
4. **Name them:**
   - Bottom layer: "Left - Artistic"
   - Top layer: "Right - Code"

---

### Step 4: Create Split Mask (3 minutes)

#### For LEFT half (Artistic):
1. **Select rectangle tool** (`R`)
2. **Draw rectangle:**
   - X: 0
   - Y: 0
   - Width: 500px
   - Height: 1200px
   - (Covers left half)
3. **Select:**
   - Rectangle + "Left - Artistic" layer
   - Right-click → "Use as mask"
   - Or: `Ctrl + Cmd + M` (Mac) / `Ctrl + Alt + M` (Windows)

#### For RIGHT half (Code):
1. **Draw another rectangle:**
   - X: 500px
   - Y: 0
   - Width: 500px
   - Height: 1200px
   - (Covers right half)
2. **Select:**
   - Rectangle + "Right - Code" layer
   - Right-click → "Use as mask"

**✅ Now you have clean left/right split!**

---

### Step 5: Style LEFT Half - Artistic (Already Done!)

The watercolor effect is already perfect! 

**Optional adjustments:**
- Slightly increase saturation (make colors pop)
- Add subtle glow effect
- Leave as-is (it's beautiful!)

---

### Step 6: Style RIGHT Half - Code Effect (15-20 minutes)

This is where the magic happens!

#### Option A: Code Text Overlay (Easier - 15 min)

1. **Create text boxes** with code snippets:
   - Press `T` (text tool)
   - Click on right half
   - Paste code (see examples below)

2. **Use monospace font:**
   - Font: **Fira Code** or **Monaco** or **Courier**
   - Size: Mix of 8px, 10px, 12px
   - Color: #0F172A (dark slate)

3. **Arrange 8-10 text boxes** with code:
   ```
   const designer = {
     skills: ['UX', 'UI', 'Research']
   }
   ```
   ```
   <div className="creative">
     <Design />
   </div>
   ```
   ```
   function solve(problem) {
     return solution;
   }
   ```
   ```
   .designer {
     mindset: analytical;
     approach: data-driven;
   }
   ```

4. **Overlay on face:**
   - Arrange text to follow face shape
   - Vary opacity: 70-100%
   - Some text boxes darker, some lighter
   - Create depth

5. **Add transparency effect:**
   - Select "Right - Code" layer
   - Reduce opacity to 30-40%
   - Text shows through with face visible

#### Option B: Typography Portrait (Advanced - 30 min)

1. **Create dense code pattern:**
   - Many small text boxes
   - Characters: `{}[]<>/\;:().`
   - Sizes: 6px to 14px
   - Overlap slightly

2. **Mask with face luminosity:**
   - Duplicate original image
   - Desaturate (remove color)
   - Adjust brightness/contrast
   - Use as mask for text layer
   - Darker face areas = more/darker text
   - Lighter areas = less/lighter text

3. **Refine:**
   - Add more text where face is dark
   - Reduce where face is light
   - Keep face recognizable!

---

### Step 7: Add Center Divider (2 minutes)

1. **Draw line:**
   - Line tool (`L`)
   - Vertical line at X: 500px
   - Height: 1200px

2. **Style:**
   - Stroke: 2px
   - Color: #E5E7EB (light gray)
   - Opacity: 50%

3. **Optional gradient:**
   - Top: fade out (0% opacity)
   - Middle: solid (50% opacity)
   - Bottom: fade out (0% opacity)

---

### Step 8: Final Adjustments (5 minutes)

1. **Check readability:**
   - Face still recognizable? ✓
   - Left/right balance? ✓
   - Not too busy? ✓

2. **Add subtle effects:**
   - Slight shadow behind text (optional)
   - Glow on divider line (optional)
   - Adjust overall contrast

3. **Color harmony:**
   - Left: Warm tones (orange, coral, yellow)
   - Right: Cool tones (slate, blue-gray)
   - Smooth transition at center

---

### Step 9: Export (2 minutes)

1. **Select frame** "Hero Image"
2. **Export settings:**
   - Format: **JPG**
   - Quality: **90%**
   - Scale: **1x**

3. **Export:**
   - Click "Export Hero Image"
   - Save as: `hero-split.jpg`
   - Check file size < 500KB
   - If too large: reduce quality to 80%

4. **Save to:**
   ```
   /Users/marikacapraro/repos/portfolio/assets/images/hero-split.jpg
   ```
   (Replace the temporary one)

---

## Code Snippets to Use

Copy/paste these into your text boxes:

### JavaScript/React:
```javascript
const create = () => {
  return magic;
}
```

```javascript
<Hero>
  <Design />
  <Code />
</Hero>
```

```javascript
function solve(problem) {
  const solution = analyze(data);
  return solution;
}
```

### CSS:
```css
.designer {
  mindset: analytical;
  approach: problem-first;
}
```

```css
.portfolio {
  display: flex;
  justify-content: space-between;
}
```

### HTML:
```html
<div class="ux-designer">
  <Experience />
  <Creativity />
</div>
```

### Mix of Symbols:
```
{ } [ ] < > / \ ; : ( ) . = + - * & %
```

---

## Layout Reference

```
┌────────────────────────────────────────┐
│                    │                   │
│    WATERCOLOR      │    CODE/TEXT     │
│    (artistic)      │    (technical)   │
│                    │                   │
│    Your face       │    Your face     │
│    with warm       │    with code     │
│    colors          │    overlay       │
│                    │                   │
│    Orange, coral   │    Slate, dark   │
│    yellow tones    │    blue-gray     │
│                    │                   │
│    DESIGNER        │    DEVELOPER     │
│                    │                   │
└────────────────────────────────────────┘
         500px      divider     500px
```

---

## Quick Tips

### Do's ✅
- Keep face recognizable on BOTH sides
- Balance artistic and technical elements
- Use consistent code theme (pick React OR vanilla)
- Make code text readable (not too small)
- Test at different sizes (looks good small too)

### Don'ts ❌
- Don't make code text too dense (overwhelming)
- Don't obscure your face too much
- Don't mix too many code styles
- Don't forget to check file size
- Don't skip the center divider (helps define split)

---

## Time Breakdown

- Setup canvas: 2 min
- Import & duplicate: 2 min
- Create masks: 3 min
- Left side (done!): 0 min
- Right side code: 15-20 min
- Center divider: 2 min
- Final touches: 5 min
- Export: 2 min

**Total: 30-35 minutes**

---

## Troubleshooting

### "Face not visible on right side"
- Reduce text opacity
- Use lighter text color
- Make image layer more visible (increase opacity)

### "Code text too busy"
- Use fewer text boxes (6-8 instead of 10-12)
- Increase spacing between lines
- Use larger font sizes (10-14px)

### "File size too large"
- Reduce export quality to 80%
- Or resize to 900×1080px, then scale up
- Use JPG, not PNG

### "Sides don't balance"
- Adjust left side saturation
- Add slight filter to right side
- Check divider is exactly at 500px

---

## Alternative Quick Method

### If you're short on time:

1. Use existing watercolor for LEFT (done!)
2. For RIGHT: Just desaturate + add 3-4 large code snippets
3. Add divider
4. Export
5. **Time: 15 minutes!**

---

## Before You Start - Checklist

- [ ] Figma account ready
- [ ] Watercolor image downloaded
- [ ] 30 minutes set aside
- [ ] Read through this guide once
- [ ] Code snippets copied (above)
- [ ] Export location ready

---

## After You Create It

1. **Save to:** `assets/images/hero-split.jpg`
2. **Refresh browser** - see your new hero!
3. **Check mobile view** (Chrome DevTools)
4. **Share with me** for feedback! 🎨

---

## Need Help?

If you get stuck on:
- Masking the split
- Code text layout
- Export settings
- Anything else

**Just ask!** I can give more specific guidance.

---

## Inspiration Tips

**Think of it like this:**
- LEFT = Heart (creative, colorful, warm)
- RIGHT = Brain (logical, structured, cool)
- YOU = Both combined perfectly!

This visual instantly communicates your unique value: **You bridge design and code.**

---

**Ready to create?** Open Figma and let's go! 🚀

**Current status:** Your watercolor image is already live on the portfolio (looks great!)  
**Next level:** Create this split version to show Designer + Developer identity!
