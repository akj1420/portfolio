# Portfolio Website Setup Instructions

## Quick Start Guide for Your Professional Portfolio

### Project Overview
This is a professional portfolio website built with HTML, CSS, and JavaScript. It showcases your CV, education, work experience, achievements, and professional details as an AML Compliance Specialist.

### Files Included
1. **index.html** - Main website structure and content
2. **style.css** - Professional styling with gradient header and responsive design
3. **script.js** - Interactive features and smooth scrolling
4. **SETUP.md** - This setup guide

---

## Step 1: Customize Your Content

Edit `index.html` and update:
- Your name (currently "Abel Koshy Joji")
- Your contact information (email, phone)
- Your location
- Professional summary
- Education details
- Work experience
- Achievements and certifications
- Skills
- Projects

---

## Step 2: Add Your Profile Photo

1. Save your professional photo as `profile.jpg` in the repository root folder
2. Recommended dimensions: 500x500 pixels (will be cropped to circle)
3. Ensure the image is a recent professional headshot
4. Upload it to GitHub by:
   - Going to your repository
   - Click "Add file" > "Upload files"
   - Select your `profile.jpg` file
   - Commit the changes

---

## Step 3: Deploy to GitHub Pages (Make it Live!)

### Option A: Automatic Deployment
1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select "main" branch as source
4. Click "Save"
5. Your site will be live at: `https://akj1420.github.io/portfolio`

### Option B: Deploy to Your Own Domain
1. Follow Option A first
2. In repository settings, add your custom domain
3. Update your domain's DNS settings to point to GitHub Pages

---

## Step 4: Optional Customizations

### Change Color Scheme
Edit `style.css` to change the header gradient:
```css
header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* Change these hex codes to your preferred colors */
}
```

### Popular Color Combinations:
- **Professional Blue**: #0066cc to #0099ff
- **Tech Dark**: #1a1a2e to #16213e
- **Compliance Green**: #0d7377 to #14919b
- **Corporate Purple**: #667eea to #764ba2 (current)

### Add More Sections
Duplicate a section in `index.html` and customize:
```html
<section id="new-section">
    <h2>Your Section Title</h2>
    <p>Your content here...</p>
</section>
```

---

## Step 5: Update Your README.md

Edit the main `README.md` with:
1. Brief introduction
2. Link to your live portfolio
3. Skills overview
4. Contact information
5. How to reach you

Example:
```markdown
# Hello, I'm Abel Koshy Joji

**AML Compliance Specialist | Risk Management Expert**

📍 Sharjah, UAE  
📧 abelkoshy14@gmail.com  
📱 +971 566178761

### Live Portfolio
👉 [View My Portfolio](https://akj1420.github.io/portfolio)

### About Me
Dynamic AML Compliance Specialist with expertise in regulatory frameworks, risk management, and financial crime prevention.
```

---

## Step 6: Share Your Portfolio

Add your portfolio link to:
- LinkedIn profile
- CV/Resume
- Email signature
- Job applications
- Portfolio platforms (Behance, Dribbble, etc.)

---

## Troubleshooting

### Portfolio not showing?
- Wait 5 minutes for GitHub Pages to deploy
- Check if GitHub Pages is enabled in settings
- Verify the branch is set to "main"
- Check browser cache (Ctrl+Shift+Delete)

### Profile photo not appearing?
- Ensure file is named exactly `profile.jpg` (case-sensitive)
- Verify image is in repository root folder
- Check file size (should be < 2MB)
- Refresh the page (Ctrl+F5)

### Styling looks broken?
- Clear browser cache
- Check that `style.css` is in the root folder
- Ensure HTML links to correct file paths

### Need to update content?
- Edit files directly in GitHub interface
- Or clone the repo locally, edit, and push changes

---

## Local Development (Optional)

To run locally before publishing:

1. Clone the repository:
   ```bash
   git clone https://github.com/akj1420/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your browser directly (no server needed)

3. Make changes to HTML/CSS/JS files

4. Push changes to GitHub:
   ```bash
   git add .
   git commit -m "Updated portfolio content"
   git push origin main
   ```

---

## SEO Optimization

Add meta tags to `index.html` for better search visibility:
```html
<meta name="description" content="Abel Koshy Joji - AML Compliance Specialist Portfolio">
<meta name="keywords" content="AML, Compliance, Risk Management, Financial Crime">
<meta name="author" content="Abel Koshy Joji">
```

---

## Browser Compatibility

Tested and working on:
- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## Performance Tips

1. **Optimize images**: Keep profile photo under 500KB
2. **Minimize scrolling sections**: Keep content focused
3. **Test on mobile**: Use browser DevTools (F12)
4. **Monitor site speed**: Use Google PageSpeed Insights

---

## Need Help?

- GitHub Documentation: https://docs.github.com/en/pages
- HTML Reference: https://developer.mozilla.org/en-US/docs/Web/HTML
- CSS Reference: https://developer.mozilla.org/en-US/docs/Web/CSS
- Contact: abelkoshy14@gmail.com

---

## Version History

**v1.0 (Current)**
- Initial portfolio setup
- Responsive design
- Smooth animations
- Dark header with gradient
- Mobile-friendly layout

---

**Last Updated:** December 2025  
**Repository:** https://github.com/akj1420/portfolio  
**Live Site:** https://akj1420.github.io/portfolio
