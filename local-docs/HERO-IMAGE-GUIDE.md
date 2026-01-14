# Hero Split-Face Image Creation Guide

## Concept
Create a split portrait that represents **Designer | Developer** - your unique dual identity.

**Left Half:** Artistic/Creative (Watercolor effect with warm colors)  
**Right Half:** Technical/Code (Face formed by code snippets)

## Specifications

### Dimensions
- **Size:** 1000px (W) × 1200px (H)
- **Format:** JPG or PNG
- **File size:** Keep under 500KB for web performance

### Base Photo
Use: **Forest photo with plaid coat** (the one where you're standing straight)

## Method 1: Figma (Recommended)

### Step 1: Set Up Canvas
1. Create new file: 1000 × 1200px
2. Import your base photo
3. Scale to fit canvas (centered)

### Step 2: Create Split Mask
1. Draw a rectangle covering left half (0 to 500px)
2. Duplicate photo layer
3. Mask one layer with rectangle (left side)
4. Keep other layer for right side

### Step 3: Left Side - Artistic Effect
1. Apply effects to left half:
   - Blur: 2-4px (subtle)
   - Color overlay: Use warm gradient
     - Top: #F59E0B (amber)
     - Middle: #EF4444 (red)  
     - Bottom: #EC4899 (pink)
   - Blend mode: Multiply or Overlay (30-50% opacity)

2. Add watercolor texture:
   - Find free watercolor PNG overlays online
   - Place on top with blend mode
   - Use colors: warm amber, coral, peach

### Step 4: Right Side - Code Effect

**Option A: Simple Code Overlay**
1. Create text boxes with code snippets:
```
<html>
  <body>
    <div class="designer">
      const create = () => {
        return magic;
      }
    </div>
  </body>
</html>
```

2. Arrange text to follow face contours:
   - Use multiple text boxes
   - Varying font sizes (8px - 14px)
   - Font: Fira Code or Monaco (monospace)
   - Colors: #0F172A (dark) with some #475569 (lighter)

3. Add mask to reveal face shape:
   - Duplicate original photo
   - Desaturate (black & white)
   - Use as luminosity mask
   - Code text follows face shadows/highlights

**Option B: Code Typography Portrait**
1. Use smaller code characters arranged densely
2. Characters: `{}[]<>/\;:().=+-*&%$#@!`
3. Vary size and opacity based on face values:
   - Dark areas: More characters, darker
   - Light areas: Fewer characters, lighter

### Step 5: Center Line
1. Add subtle vertical line at center (500px)
2. Color: #E5E7EB
3. Width: 2-3px
4. Optional: Slight gradient fade at top/bottom

### Step 6: Export
1. File → Export
2. Format: JPG (90% quality)
3. Name: `hero-split.jpg`
4. Check file size < 500KB

## Method 2: Photoshop

### For Left Side (Artistic):
1. **Adjustment Layers:**
   - Hue/Saturation → Colorize
   - Color Balance → Add warm tones
   - Vibrance → Increase slightly

2. **Watercolor Effect:**
   - Filter → Filter Gallery → Artistic → Watercolor
   - Or download watercolor brushes/overlays

3. **Add Texture:**
   - Layer watercolor texture PNG
   - Blend mode: Overlay or Soft Light
   - Opacity: 40-60%

### For Right Side (Code):
1. **Create Code Text:**
   - Type tool with monospace font
   - Multiple layers of code snippets
   - Arrange to follow face shape

2. **Mask with Face:**
   - Convert photo to black & white
   - Use Threshold adjustment
   - Use as mask for code text layer

3. **Refine:**
   - Vary text opacity (darker where face is darker)
   - Add slight blur to background text
   - Keep face edges sharp

## Method 3: Online Tools (Quick Option)

### Using Canva:
1. Upload your photo
2. Use "Duotone" effect on left side with warm colors
3. For right side:
   - Add text boxes with code
   - Use "Photo" effect → "Halftone" or "Sketch"
   - Overlay with code text

### Using Photopea (Free Photoshop Alternative):
- Same steps as Photoshop method
- Free online tool: photopea.com

## Inspiration Reference

Think of these styles:

**Left Side:** 
- Watercolor portrait art
- Warm sunset colors
- Soft, artistic, creative feeling
- Similar to the guy's example with paint splatter

**Right Side:**
- Matrix-style code text
- Terminal/IDE aesthetic  
- Technical, precise, structured
- Face formed by typography

## Color Palette Reference

### Left (Warm/Artistic):
- `#F59E0B` - Amber
- `#F97316` - Orange
- `#EF4444` - Red
- `#EC4899` - Pink
- `#F472B6` - Light pink

### Right (Code/Technical):
- `#0F172A` - Deep slate (primary text)
- `#475569` - Medium slate (secondary)
- `#1E293B` - Dark slate (background hint)

## Tips for Best Results

1. **Keep face recognizable** - Don't over-process
2. **Balance is key** - Neither side should overpower
3. **Smooth transition** - Center line should be clean
4. **Test responsiveness** - Check how it looks at different sizes
5. **Optimize file size** - Compress without losing quality

## Quick Checklist

- [ ] Canvas: 1000 × 1200px
- [ ] Base photo: Forest with plaid coat
- [ ] Left side: Warm watercolor effect
- [ ] Right side: Code typography/overlay
- [ ] Center split line visible
- [ ] Face clearly recognizable
- [ ] File size < 500KB
- [ ] Named: hero-split.jpg
- [ ] Placed in: assets/images/

## Need Help?

If you get stuck or want me to review drafts:
1. Share the work-in-progress
2. I can give specific feedback
3. We can iterate until it's perfect!

---

**Remember:** This image is your portfolio's first impression - take time to make it uniquely YOU!
