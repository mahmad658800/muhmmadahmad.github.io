# Muhammad Ahmad — Odoo Developer Portfolio

A modern, professional portfolio website showcasing 2+ years of Odoo development experience with custom POS systems, integrations, and e-commerce solutions.

## 🎨 Features

✅ **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile  
✅ **Modern UI/UX** - Beautiful gradient designs with smooth animations  
✅ **Interactive Elements** - Animated counters, skill bars, and project filters  
✅ **Project Showcase** - 8+ detailed project case studies with technologies  
✅ **Contact Form** - Functional form with EmailJS integration  
✅ **Fast Performance** - Optimized for quick load times  
✅ **SEO Optimized** - Meta tags and structured data included  

## 📁 File Structure

```
your-portfolio/
├── index.html      # Main HTML file
├── style.css       # All styling
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🚀 Getting Started

### Option 1: Direct Upload to GitHub Pages

1. **Create a new GitHub repository** named `your-username.github.io`
2. **Clone the repository** to your computer
3. **Copy these 3 files** into the repository:
   - `index.html`
   - `style.css`
   - `script.js`
4. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Add portfolio"
   git push origin main
   ```
5. **Visit** `https://your-username.github.io` to see your portfolio live!

### Option 2: Local Testing

1. Create a folder called `my-portfolio`
2. Add the 3 files to this folder
3. Open `index.html` in your web browser
4. Make changes and refresh to see updates

## ⚙️ Setup Instructions

### 1. Update Your Information

Edit `index.html` and find these sections:

**Line 19-21**: Update meta description
```html
<meta name="description"
      content="Muhammad Ahmad is an Odoo Developer..."/>
```

**Line 22**: Update canonical URL
```html
<link rel="canonical" href="https://your-github-username.github.io/"/>
```

**Line 28-29**: Update Open Graph data
```html
<meta property="og:url" content="https://your-github-username.github.io/"/>
```

### 2. Set Up Contact Form (EmailJS)

The contact form currently won't send emails. To enable it:

1. **Sign up at** [EmailJS](https://www.emailjs.com) (free account)
2. **Create a Service** and get your `Service ID`
3. **Create a Template** for emails and get your `Template ID`
4. **Get your Public Key** from Account settings
5. **Edit `script.js`** (lines 10-12) and replace:
   ```javascript
   const EMAILJS_PUBLIC_KEY  = 'your_public_key_here';
   const EMAILJS_SERVICE_ID  = 'your_service_id_here';
   const EMAILJS_TEMPLATE_ID = 'your_template_id_here';
   ```

### 3. Update Profile Information

- **Name**: Change "Muhammad Ahmad" throughout the file
- **Title**: Change "Odoo Developer" as needed
- **Email**: Change `mahmad658800@gmail.com` to your email
- **Phone**: Change `+92-323-4765880` to your phone number
- **LinkedIn**: Update the LinkedIn URL
- **Avatar**: Replace avatar-initials with your own initials or add a profile photo

### 4. Customize Projects

Each project section follows this pattern:
```html
<div class="project-card" data-category="retail" data-aos="fade-up">
    <!-- Project details -->
</div>
```

**Categories available**: `retail`, `food`, `ecommerce`, `integration`

### 5. Update Skills

Edit the skill bars in the Skills section. Each skill has:
- A name
- A percentage (0-100)
- A data-width attribute

Example:
```html
<div class="skill-bar-item">
    <div class="skill-bar-label"><span>Odoo Development</span><span>92%</span></div>
    <div class="skill-bar-track">
        <div class="skill-bar-fill" data-width="92"></div>
    </div>
</div>
```

## 📊 Customization

### Colors

Edit `style.css` at the top to change the color scheme:
```css
:root {
  --primary: #7c3aed;           /* Purple */
  --accent: #3b82f6;            /* Blue */
  --secondary: #a78bfa;         /* Light purple */
  --success: #10b981;           /* Green */
  /* ... other colors ... */
}
```

### Fonts

The portfolio uses:
- **Display**: Syne (headings)
- **Body**: DM Sans (text)

To change fonts, edit the Google Fonts import in `index.html` (lines 42-43).

### Animations

All animations are controlled by `data-aos` attributes. Check the [AOS Library docs](https://michalsnik.github.io/aos/) for options.

## 🔧 Troubleshooting

### Contact form not sending?
- Check EmailJS is set up correctly
- Verify Public Key, Service ID, and Template ID are correct
- Check browser console for errors (F12)

### Portfolio not showing on GitHub?
- Wait 1-2 minutes for GitHub Pages to deploy
- Check repository name is `username.github.io`
- Ensure files are pushed to main branch

### Styling looks broken?
- Clear browser cache (Ctrl+Shift+Delete)
- Try a different browser
- Check all 3 files are in the repository

### Animations not smooth?
- This is normal on older devices
- Animations are optional, content is still visible
- Check browser developer console for errors

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Laptop**: 900px - 1200px
- **Tablet**: 640px - 900px
- **Mobile**: 380px - 640px
- **Small Mobile**: < 380px

## 🎯 SEO Tips

The portfolio includes:
- ✅ Meta descriptions
- ✅ Open Graph tags for social sharing
- ✅ Schema markup (structured data)
- ✅ Semantic HTML
- ✅ Fast loading time

To improve SEO further:
1. Add a sitemap.xml
2. Submit to Google Search Console
3. Write quality project descriptions
4. Get backlinks from LinkedIn and other profiles

## 🔒 Security

- No sensitive information is stored
- Contact form uses EmailJS (secure third-party service)
- No server-side code needed
- Safe for GitHub Pages hosting

## 📄 License

Free to use and modify for personal use.

## ✨ Tips for Best Results

1. **High-quality content**: Write detailed project descriptions
2. **Keep it updated**: Add new projects and update skills regularly
3. **Test on devices**: Check on mobile, tablet, and desktop
4. **Share on social media**: Add your portfolio link to LinkedIn and Twitter
5. **Get feedback**: Share with colleagues and get their thoughts

## 🆘 Need Help?

- Check the original portfolio at: https://waqarahmad403.github.io/waqar-portfolio/
- Review HTML/CSS/JS syntax
- Test in browser console for errors
- Compare your code with the template

## 🚀 Next Steps

1. ✅ Customize all personal information
2. ✅ Set up EmailJS for contact form
3. ✅ Add your profile photo (optional)
4. ✅ Create GitHub Pages repository
5. ✅ Push all files
6. ✅ Share your portfolio link
7. ✅ Update LinkedIn with portfolio URL

---

**Built with passion for Odoo development and business transformation.**

Good luck with your portfolio! 🎉
