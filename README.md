# Rituparna Chakrabarti - Academic Portfolio

A minimalist, elegant academic portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing research, publications, and professional accomplishments.

## 📋 Features

- **Minimalist Design**: Clean, focused aesthetic with elegant typography
- **Responsive Layout**: Fully responsive on mobile, tablet, and desktop
- **Smooth Animations**: Subtle fade-in animations and hover effects
- **Easy to Customize**: Well-organized code with CSS variables for quick theming
- **SEO Ready**: Semantic HTML structure
- **No Dependencies**: Pure HTML/CSS/JavaScript—no frameworks required

## 🚀 Quick Setup on GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and sign in
2. Create a new repository named `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
3. Make it public

### Step 2: Upload Your Files
1. Clone the repository to your computer:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   ```

2. Copy these files into the repository folder:
   - `index.html`
   - `styles.css`
   - `script.js`

3. Add your profile photo (see instructions below)

4. Commit and push:
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```

### Step 3: Enable GitHub Pages
1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Build and deployment," select `main` branch
4. Click "Save"

Your site will be live at `https://yourusername.github.io` in a few minutes!

## 🖼️ Your Portfolio Includes

✅ **Heart Illustration** - A beautiful cardiovascular research illustration featured prominently in your hero section
- Perfect for showcasing your research focus on atherosclerosis and vascular inflammation
- The image is already integrated and responsive

If you want to modify or replace the heart image:
1. Simply replace `heart.png` with your new image (keep the same filename)
2. The styling will automatically adapt

## 🎨 Customization Guide

### Change Colors
Edit the CSS variables at the top of `styles.css`:

```css
:root {
    --primary: #1a1a1a;        /* Dark text */
    --accent: #0066cc;         /* Blue accent (change this!) */
    --bg: #ffffff;             /* Background */
    --bg-alt: #fafafa;         /* Alternate background */
    /* ... other variables ... */
}
```

### Change Fonts
Replace serif and sans-serif fonts in `styles.css`:
```css
--font-serif: 'Georgia', 'Garamond', serif;
--font-sans: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
```

Popular alternatives:
- **Serif**: 'Playfair Display', 'EB Garamond', 'Lora'
- **Sans-serif**: 'Inter', 'Poppins', 'Raleway'

### Update Social Links
In `index.html`, update the Contact section:
```html
<a href="https://www.linkedin.com/in/yourprofile/" class="contact-link" target="_blank">
    <span class="contact-label">LinkedIn</span>
    <span class="contact-value">LinkedIn Profile</span>
</a>
```

## 📱 Responsive Breakpoints

The design is optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: 480px to 767px
- **Small Mobile**: Below 480px

## ✨ Features Explained

### Navigation
- Sticky header with smooth scroll-to links
- Active link highlighting
- Hover effects with animated underlines

### Hero Section
- Large, elegant typography
- Animated fade-in on page load
- Call-to-action buttons

### Timeline (Education)
- Visual timeline with markers
- Clean chronological layout

### Experience & Skills
- Hover effects on cards
- Icon-style bullets (→)
- Organized grid layouts

### Publications
- Organized by type (Articles, Reviews, Books, Conferences)
- Easy to update and maintain

### Contact
- Simple, clean contact section
- Email and social links

## 🔧 Advanced Customization

### Add Google Analytics
Add this before the closing `</head>` tag in `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_ID');
</script>
```

Replace `GA_ID` with your Google Analytics ID.

### Add Dark Mode
Add this to the top of `styles.css`:
```css
@media (prefers-color-scheme: dark) {
    :root {
        --primary: #f0f0f0;
        --bg: #1a1a1a;
        --bg-alt: #2a2a2a;
        --border: #404040;
        --text: #f0f0f0;
        --text-light: #b0b0b0;
    }
}
```

## 📂 File Structure

```
yourusername.github.io/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
├── heart.png           # Your cardiovascular research illustration
└── README.md           # Documentation
```

## 🐛 Troubleshooting

### Site not showing up?
- Make sure repository name is exactly `yourusername.github.io`
- Wait 2-3 minutes after pushing changes
- Check GitHub Pages settings in repository Settings > Pages

### Images not loading?
- Use relative paths: `./profile.png` or `profile.png`
- Ensure image file is in the same directory as `index.html`
- Check file name capitalization (case-sensitive on GitHub)

### Styling looks different?
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Try a different browser
- Check that `styles.css` is in the same folder as `index.html`

## 📝 SEO Tips

1. Update the `<title>` in `index.html` with your name and title
2. Add meta description:
   ```html
   <meta name="description" content="Postdoctoral Fellow in Cardiovascular Immunology. PhD from IIT Kharagpur.">
   ```
3. Add your social profiles in the footer
4. Make sure all links work correctly

## 🎯 Next Steps

1. ✅ Upload files to GitHub
2. ✅ Add your profile photo
3. ✅ Customize colors and fonts
4. ✅ Update all text with your information
5. ✅ Test on mobile devices
6. ✅ Share your portfolio!

## 📄 License

This template is free to use and modify for personal use.

---

**Questions or Issues?**
- Check the HTML/CSS code—it's well-commented
- Review the GitHub Pages documentation
- Visit [Stack Overflow](https://stackoverflow.com) for web development help

Happy coding! 🚀
