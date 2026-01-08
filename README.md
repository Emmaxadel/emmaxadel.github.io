# Emmanuel Adeleye - Portfolio Website

A modern, responsive portfolio website showcasing my journey as a Data Scientist and Bioinformatics Researcher.

## 🌟 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Dynamic navigation, scroll animations, and hover effects
- **SEO Optimized** - Proper meta tags and semantic HTML structure
- **Fast Loading** - Lightweight code with optimized performance
- **Easy to Customize** - Well-organized code with clear comments

## 🚀 Sections

1. **Hero** - Eye-catching introduction with call-to-action buttons
2. **About** - Professional summary with key statistics
3. **Skills** - Technical skills organized by category
4. **Projects** - Showcase of data science and research projects
5. **Experience** - Professional and leadership timeline
6. **Education** - Academic qualifications and certifications
7. **Contact** - Multiple ways to get in touch

## 📁 File Structure

```
Portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (Vanilla)** - Interactive features
- **Font Awesome** - Icons
- **Google Fonts** - Typography (loaded via system fonts)

## 📦 Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. **Create a GitHub account** (if you don't have one):
   - Go to [github.com](https://github.com)
   - Click "Sign up"

2. **Create a new repository**:
   - Click the "+" icon → "New repository"
   - Name it: `your-username.github.io` (e.g., `emmanuel-adeleye.github.io`)
   - Make it public
   - Click "Create repository"

3. **Upload your files**:
   - Click "uploading an existing file"
   - Drag and drop: `index.html`, `styles.css`, `script.js`
   - Commit changes

4. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Under "Source", select "main" branch
   - Click "Save"

5. **Access your site**:
   - Your portfolio will be live at: `https://your-username.github.io`
   - It may take 5-10 minutes to deploy

### Option 2: Netlify (Alternative - Free)

1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub
3. Click "Add new site" → "Deploy manually"
4. Drag your portfolio folder
5. Your site will be live instantly with a random URL
6. You can customize the URL in site settings

### Option 3: Vercel (Alternative - Free)

1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your repository
4. Click "Deploy"
5. Your site will be live with a vercel.app URL

## ✏️ Customization Guide

### 1. Update Your Information

**Personal Details** (in `index.html`):
- Update your name, title, and description
- Change email, phone, and location
- Add your LinkedIn and GitHub URLs

**Projects**:
- Replace project links (search for `href="#"`)
- Update project descriptions
- Add your GitHub repository links

### 2. Add Your GitHub Username

In `index.html`, line 26:
```html
<a href="https://github.com/yourgithub" target="_blank" aria-label="GitHub">
```
Replace `yourgithub` with your actual GitHub username.

### 3. Change Colors

In `styles.css`, update the CSS variables at the top:
```css
:root {
    --primary-color: #2563eb;    /* Main blue color */
    --secondary-color: #0ea5e9;  /* Light blue */
    --accent-color: #f59e0b;     /* Orange/yellow */
}
```

### 4. Add More Projects

Copy a project card in `index.html` and modify:
```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Your Project Name</h3>
    <p>Project description...</p>
    <div class="project-tags">
        <span>Technology 1</span>
        <span>Technology 2</span>
    </div>
    <div class="project-links">
        <a href="your-github-link" class="project-link">
            <i class="fab fa-github"></i> Code
        </a>
    </div>
</div>
```

### 5. Add Profile Image (Optional)

Add this code in the About section:
```html
<div class="about-image">
    <img src="your-image.jpg" alt="Emmanuel Adeleye">
</div>
```

And add corresponding CSS in `styles.css`.

## 📱 Testing Your Portfolio

Before deploying, test locally:

1. **Open the file**:
   - Double-click `index.html` in File Explorer
   - It will open in your default browser

2. **Test responsiveness**:
   - Press F12 to open Developer Tools
   - Click the device toggle icon
   - Test on different screen sizes

3. **Check all links**:
   - Click every navigation link
   - Test all external links
   - Verify social media links work

## 🔧 Troubleshooting

**Images not showing?**
- Make sure image files are in the same folder as `index.html`
- Use relative paths: `src="./image.jpg"`

**Animations not working?**
- Ensure `script.js` is in the same folder
- Check browser console (F12) for errors

**Layout broken on mobile?**
- Clear browser cache
- Test in incognito/private mode

**GitHub Pages not showing updates?**
- Clear browser cache
- Wait 5-10 minutes for deployment
- Check repository settings

## 🎨 Future Enhancements

Consider adding:
- [ ] Blog section for articles
- [ ] Contact form with backend
- [ ] Dark mode toggle
- [ ] More project showcases
- [ ] Testimonials section
- [ ] Resume download button
- [ ] Analytics tracking
- [ ] Custom domain name

## 📝 Custom Domain (Optional)

To use a custom domain (e.g., `emmanueladeleye.com`):

1. **Buy a domain** from:
   - Namecheap
   - GoDaddy
   - Google Domains

2. **Configure DNS**:
   - Add CNAME record pointing to `your-username.github.io`

3. **Update GitHub Pages**:
   - Go to Settings → Pages
   - Add custom domain
   - Enable HTTPS

## 🤝 Need Help?

- Check [GitHub Pages Documentation](https://docs.github.com/en/pages)
- Visit [MDN Web Docs](https://developer.mozilla.org/) for HTML/CSS/JS help
- Ask on [Stack Overflow](https://stackoverflow.com/)

## 📄 License

This portfolio template is free to use and modify for your personal portfolio.

## 🙏 Acknowledgments

- Font Awesome for icons
- Inspiration from modern portfolio designs
- Built with passion for showcasing data science skills

---

**Built by Emmanuel Adeleye | 2026**

For questions or collaborations, reach out at: adeleyee45@gmail.com
