# Expert Alliance AI Investor Deck - Import Guide

## Quick Start: Google Slides Import (Recommended)

### Method 1: Copy-Paste from Markdown (Fastest)

1. **Open Google Slides**: https://slides.google.com
2. **Create blank presentation**: Click "Blank" template
3. **Open the markdown file**: `investor-deck-export.md`
4. **Create slides manually**:
   - Each `---` separator = new slide
   - Copy slide content between separators
   - Apply formatting using toolbar

**Slide Layout Mapping:**
- Headers (`#`) → Title text boxes
- Subheaders (`##`) → Subtitle text boxes  
- Bullets (`-`) → Bullet point lists
- Tables → Insert → Table (copy cell by cell)

### Method 2: PowerPoint Desktop App

1. **Open PowerPoint** (Microsoft 365 or desktop version)
2. **Create new presentation**: Blank template
3. **Open markdown file**: `investor-deck-export.md`
4. **Create slides using content**:
   - Right-click slide panel → "New Slide"
   - Copy content from markdown
   - Format using PowerPoint tools

**Tips:**
- Use "Title and Content" layout for most slides
- Use "Title Only" for slides with custom layouts (grid, timeline)
- Insert tables via "Insert → Table"

### Method 3: LibreOffice Impress (Free Alternative)

1. **Download LibreOffice**: https://www.libreoffice.org/download
2. **Open Impress** (presentation software)
3. **Import markdown** via:
   - File → Open → Select "Text CSV (.csv .txt)" file type
   - Choose `investor-deck-export.md`
   - Manual formatting required

## Slide Content Reference

### Slide 1: Title Slide
- **Logo**: Centered, 100px
- **Title**: "EXPERT ALLIANCE AI"
- **Subtitle**: "Transforming Corporate Travel Procurement"
- **Tagline**: "$1.5T Market Opportunity"

### Slides 2-14: Content Slides
- **Logo**: Top-right corner, 35px
- **Section Title**: Left side of header
- **Content**: Bullets, grids, tables, timelines

### Slide 15: Contact Slide
- **Logo**: Centered, 100px
- **Title**: "LET'S TALK"
- **Contact Info**: Name, title, email, phone, location

## Design Specifications

**Color Palette:**
- Primary Purple: `#667eea`
- Secondary Purple: `#764ba2`
- Pink Gradient: `#f093fb` → `#f5576c`
- Light Background: `#f8f9fa`
- Success Green: `#d4edda`

**Typography:**
- Font: Segoe UI (or Roboto, Helvetica, Arial)
- Title (h1): 2.8rem / 42pt
- Section (h2): 2rem / 30pt
- Subsection (h3): 1.4rem / 21pt
- Body: 1.1rem / 16pt

**Spacing:**
- Slide padding: 60px top/bottom, 45px left/right
- Grid gap: 20px
- Card padding: 15px

## Troubleshooting

### "Table not formatting correctly"
**Solution**: Create table first in Slides, then copy cell-by-cell from markdown

### "Colors don't match"
**Solution**: Use color picker with hex codes from Design Specifications above

### "Logo missing"
**Solution**: Insert `ExpertAllianceAI-logo.svg` image manually
- Slide 1 & 15: Center, resize to ~100px height
- Slides 2-14: Top-right, resize to ~35px height

### "Content doesn't fit slide"
**Solution**: 
- Reduce font sizes slightly
- Adjust padding/margins
- Consider splitting content across multiple slides

## Alternative: Use HTML Version

If you need the exact design, use the HTML version:

**File**: `investor-deck.html`  
**Usage**: 
- Open in web browser
- Present directly from browser (F11 for fullscreen)
- Use arrow keys to navigate
- Print to PDF via browser (Ctrl+P → Save as PDF)

**Benefits:**
- Perfect visual fidelity
- Interactive navigation
- Consistent rendering across devices
- No conversion required

## Need Help?

- Original HTML deck: `investor-deck.html` (open in browser)
- Markdown source: `investor-deck-export.md` (for conversion)
- Logo files: `ExpertAllianceAI-logo.svg`, `ExpertAllianceAI-icon.svg`
