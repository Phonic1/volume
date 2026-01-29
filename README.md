# M6 Volume Chart Web App

A child-friendly, interactive web application to help primary school students understand and learn about different volume levels.

## Features

- Clean, bright yellow and white color scheme
- Primary school-friendly Comic Sans MS font
- Interactive clickable volume levels (0-4)
- Individual pages for each volume level with associated images
- Mobile-responsive design
- Smooth hover animations

## Volume Levels

- **Level 4**: Shouting
- **Level 3**: Loud Voice
- **Level 2**: Speaking
- **Level 1**: Whisper
- **Level 0**: Silent

## GitHub Pages Deployment Instructions

### Step 1: Upload Files to GitHub

1. Create a new repository on GitHub (e.g., `m6-volume-chart`)
2. Upload all HTML files:
   - `index.html`
   - `shouting.html`
   - `loud-voice.html`
   - `speaking.html`
   - `whisper.html`
   - `silent.html`

### Step 2: Add PNG Image Files

Upload the following PNG files to the root of your repository (same folder as the HTML files):
- `shouting.png`
- `loud voice.png` (with space in filename)
- `speaking.png`
- `whisper.png`
- `silent.png`

**IMPORTANT**: The filenames must match exactly as shown above, including the space in "loud voice.png"

### Step 3: Enable GitHub Pages

1. Go to your repository's Settings
2. Scroll down to the "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select the `main` branch and `/ (root)` folder
5. Click "Save"

### Step 4: Access Your Site

After a few minutes, your site will be available at:
`https://[your-username].github.io/[repository-name]/`

## File Structure

```
repository/
├── index.html          # Main page with all volume levels
├── shouting.html       # Level 4 page
├── loud-voice.html     # Level 3 page
├── speaking.html       # Level 2 page
├── whisper.html        # Level 1 page
├── silent.html         # Level 0 page
├── shouting.png        # Level 4 image
├── loud voice.png      # Level 3 image (note: space in filename)
├── speaking.png        # Level 2 image
├── whisper.png         # Level 1 image
└── silent.png          # Level 0 image
```

## Browser Compatibility

This web app works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Mobile Support

The app is fully responsive and works on tablets and smartphones.

## Notes

- The app uses Comic Sans MS font for a friendly, child-appropriate appearance
- All pages use the same yellow (#F4D03F) and white color scheme
- Each level page includes a back button to return to the main chart
- Images should be PNG format for best quality
