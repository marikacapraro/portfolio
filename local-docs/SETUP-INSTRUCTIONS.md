# Portfolio Setup Instructions

## Quick Start - View Your Portfolio NOW!

1. **Open the portfolio:**
   - Navigate to: `/Users/marikacapraro/repos/portfolio/`
   - Double-click `index.html` to open in your browser
   - Or right-click → Open With → Your preferred browser

2. **What you'll see:**
   - Complete homepage structure ✓
   - Navigation that works ✓
   - Project filtering ✓
   - Responsive design ✓
   - **Note:** Images will show placeholders until you add them

## Adding Your Images

### Priority 1: Hero Image (Most Important!)

**What:** The split-face design (designer/developer concept)  
**Where:** `assets/images/hero-split.jpg`  
**Guide:** See `HERO-IMAGE-GUIDE.md` for detailed instructions  
**Dimensions:** 1000 × 1200px

**Temporary Solution:** 
- Use one of your forest photos for now
- Rename it to `hero-split.jpg`
- The final split-face version can replace it later

### Priority 2: About Section Images

**Image 1: About Preview**
- **File:** `assets/images/marika-about.jpg`
- **Dimensions:** 800 × 800px (square)
- **Recommended:** Forest photo with blue sweater or plaid coat
- **Where it appears:** Homepage "About Preview" section

**Image 2: Personal Section**
- **File:** `assets/images/personal-1.jpg`  
- **Dimensions:** 600 × 600px
- **Recommended:** Photo with your dog!
- **Where it appears:** About page "Beyond Design" section

### Priority 3: Project Cover Images

Create a folder: `assets/images/projects/`

For each project, export a mockup from Figma:

1. **cambio-redesign-cover.jpg** (1200 × 750px)
   - Show login flow screens
   - 2-3 screens side by side

2. **cambio-design-system-cover.jpg** (1200 × 750px)
   - Show color palette + components
   - Grid layout of tokens

3. **walk-paws-cover.jpg** (1200 × 750px)
   - Show app screens
   - Phone mockup preferred

4. **walk-paws-frontend-cover.jpg** (1200 × 750px)
   - Screenshot of live website
   - Desktop + mobile view

## Image Optimization Tips

### Before Adding Images:

1. **Resize to exact dimensions** (don't rely on CSS to scale)
2. **Compress images:**
   - Use [TinyPNG.com](https://tinypng.com/) (free, easy)
   - Or [Squoosh.app](https://squoosh.app/) (more control)
3. **Target file sizes:**
   - Hero image: < 500KB
   - About images: < 300KB each
   - Project covers: < 400KB each

### Quick Photoshop Export:
- File → Export → Export As
- Format: JPG
- Quality: 80-90%
- Check file size

### Quick Figma Export:
- Select frame/mockup
- Export settings: 2x, JPG, 80%
- Download and rename

## Testing Your Portfolio

### Browser Testing:
1. **Desktop:**
   - Chrome ✓
   - Safari ✓  
   - Firefox ✓

2. **Mobile:**
   - Open Chrome DevTools (F12)
   - Click device icon (top-left)
   - Test iPhone/Android views

### Checklist:
- [ ] All images load correctly
- [ ] Navigation works (click links)
- [ ] Mobile menu opens/closes
- [ ] Project filters work (click "UX/UI Design", "Frontend Dev")
- [ ] Smooth scrolling to sections
- [ ] Contact links work (email, LinkedIn)

## Customizing Content

### Update Your Information:

**Email Links:** Search for `marikacapraro94@gmail.com` and verify it's correct

**LinkedIn:** Update this URL if needed:
```
https://www.linkedin.com/in/marika-capraro/
```

**Resume:** Add your PDF resume to:
```
assets/Marika-Capraro-Resume.pdf
```

### Adding the New Project:

1. Share the path to your recent project conversation
2. I'll help you create the 5th project card
3. We'll add it to the projects grid

## Local Development Server (Optional)

For better testing with live reload:

### Option 1: VS Code Live Server
1. Install "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"
4. Portfolio opens at `localhost:5500`

### Option 2: Python Server
```bash
cd /Users/marikacapraro/repos/portfolio
python3 -m http.server 8000
```
Open: `http://localhost:8000`

### Option 3: Node.js Server
```bash
npx serve
```

## Common Issues & Fixes

### Images Not Showing?
- Check file names match exactly (case-sensitive!)
- Verify files are in correct folder
- Check browser console (F12) for errors

### Layout Looks Broken?
- Clear browser cache (Cmd + Shift + R)
- Check if CSS file loaded (View Source)

### Mobile Menu Not Working?
- Make sure JavaScript loaded
- Check browser console for errors

## Next Steps

1. **Add temporary images** to see full design
2. **Create hero split-face image** (use guide)
3. **Review content** on About page - edit as needed
4. **Share new project info** - I'll add it
5. **Create case study pages** - We'll do these next
6. **Test on real phone** - Not just DevTools
7. **Deploy** - Once you're happy with it!

## File Structure Reference

```
portfolio/
├── index.html                    ← Open this in browser
├── about.html                    ← About page
├── README.md                     ← Project overview
├── HERO-IMAGE-GUIDE.md          ← How to create split image
├── SETUP-INSTRUCTIONS.md        ← This file!
├── styles/
│   ├── main.css                 ← Main styles
│   └── about.css                ← About page styles
├── scripts/
│   └── main.js                  ← Interactions
└── assets/
    ├── images/
    │   ├── hero-split.jpg       ← ADD THIS
    │   ├── marika-about.jpg     ← ADD THIS  
    │   ├── personal-1.jpg       ← ADD THIS
    │   └── projects/            ← CREATE FOLDER, ADD IMAGES
    │       ├── cambio-redesign-cover.jpg
    │       ├── cambio-design-system-cover.jpg
    │       ├── walk-paws-cover.jpg
    │       └── walk-paws-frontend-cover.jpg
    └── Marika-Capraro-Resume.pdf ← ADD THIS
```

## Questions?

If anything is unclear or you need help with:
- Image creation
- Content editing
- Adding new projects
- Case study pages
- Deployment

Just let me know! We'll tackle it together.

---

**You're doing great!** 🎉 The hard part (structure & design) is done. Now it's just adding your content and making it yours.
