# Blog Images Folder

## MCC25 Folder Structure

This folder should contain the following images for the Mullai Chess Championship 2025 blog post:

### Required Images:
1. **MKCA SPONCER BANNER 123.jpg** - Main banner/thumbnail image for the blog post
2. **image1.jpg** to **image6.jpg** - Tournament scene photos showing:
   - Players in action
   - Tournament setup
   - Prize distribution ceremony
   - Opening ceremony
   - Crowd and audience
   - MKCA coaches and organizers

### Image Specifications:
- **Format**: JPG or PNG
- **Thumbnail Image**: Recommended size 800x400px or similar landscape format
- **Gallery Images**: Recommended size 600x400px for consistent grid display
- **Quality**: High resolution for clear viewing when enlarged in modal

### Adding New Blog Images:
When adding images for future blog posts:
1. Create a new folder in `/blog/` directory
2. Use descriptive folder names (e.g., `tournament-2026`, `chess-tips`, etc.)
3. Reference images in HTML using relative path: `./blog/[folder-name]/[image-name].jpg`
4. Update the `openModal()` onclick handlers for each image

### Current Structure:
```
blog/
├── MCC25/
│   ├── MKCA SPONCER BANNER 123.jpg  (main banner)
│   ├── image1.jpg  (tournament scene 1)
│   ├── image2.jpg  (tournament scene 2)
│   ├── image3.jpg  (tournament scene 3)
│   ├── image4.jpg  (tournament scene 4) 
│   ├── image5.jpg  (tournament scene 5)
│   └── image6.jpg  (tournament scene 6)
└── README.md  (this file)
```

Place your tournament images in the MCC25 folder with the exact filenames used in the HTML code.