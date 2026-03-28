# Modern Portfolio Website - Setup Instructions

## 🎯 Project Overview
A modern, responsive personal portfolio website inspired by Brittany Chiang's design. Built with clean HTML5 and CSS3, featuring a dark theme and professional layout.

## 📁 File Structure
```
modern-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet with comprehensive comments
├── js/                 # For future JavaScript additions
├── images/             # Profile pictures and project screenshots
└── assets/             # Icons, favicons, and other assets
```

## 🚀 How to Run

### Method 1: Simple File Opening
1. Download/clone all files
2. Open `index.html` directly in your web browser
3. That's it! No server required for basic functionality

### Method 2: Using Live Server (Recommended for development)
1. Install VS Code
2. Install "Live Server" extension
3. Right-click on `index.html`
4. Select "Open with Live Server"
5. Your site opens at `http://127.0.0.1:5500`

### Method 3: Using Python Simple Server
1. Open terminal/command prompt
2. Navigate to the project folder
3. Run: `python -m http.server 8000` (Python 3)
4. Open browser to `http://localhost:8000`

### Method 4: Using Node.js http-server
1. Install Node.js
2. Install http-server: `npm install -g http-server`
3. Run: `http-server`
4. Open the provided URL in your browser

## 🎨 Customization Guide

### 1. Personal Information
**File: `index.html`**
- Line 12: Update page title
- Line 30: Change email address
- Lines 35-38: Update social media links
- Lines 71-89: Update navigation name and resume link
- Lines 97-109: Update hero section text
- Lines 128-148: Modify about section content

### 2. Colors & Theme
**File: `css/style.css`**
- Lines 20-35: Color variables (--navy-dark, --cyan, etc.)
- To change accent color: modify `--cyan: #64ffda;` to your preferred color
- For light theme: swap dark and light color values

### 3. Typography
**File: `css/style.css`**
- Lines 37-38: Font families
- Lines 41-48: Font sizes
- Update Google Fonts link in HTML if changing fonts

### 4. Content Sections
**Update these sections in `index.html`:**
- **About**: Lines 128-148
- **Skills**: Lines 162-210  
- **Projects**: Lines 223-380
- **Contact**: Lines 394-410

## 📱 Responsive Breakpoints
- **Desktop**: 1200px+
- **Tablet**: 768px - 1200px
- **Mobile**: 480px - 768px
- **Small Mobile**: < 480px

## 🔧 Adding Your Content

### Profile Picture
1. Add your image to `images/` folder
2. Update line 146: Replace placeholder URL with `images/your-photo.jpg`

### Project Images
1. Add screenshots to `images/` folder
2. Update image sources in project sections (lines 280, 320, etc.)

### Resume/CV
1. Add PDF to `assets/` folder
2. Update line 89: `href="assets/your-resume.pdf"`

### Favicon
1. Add favicon files to `assets/` folder
2. Update line 13: `href="assets/favicon.ico"`

## 🎯 SEO Optimization
The template includes:
- Semantic HTML5 structure
- Meta description and keywords
- Proper heading hierarchy
- Alt text for images
- Accessible navigation

## ♿ Accessibility Features
- Skip to main content link
- ARIA labels
- Keyboard navigation support
- Screen reader friendly
- High contrast colors
- Focus indicators

## 🔍 Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📚 Technologies Used
- **HTML5**: Semantic structure
- **CSS3**: Modern styling with Grid & Flexbox
- **CSS Variables**: Easy theme customization
- **CSS Grid**: Responsive layouts
- **Flexbox**: Component alignment
- **CSS Animations**: Smooth transitions

## 🛠️ Development Tips

### Beginner Friendly Features
1. **Extensive Comments**: Every section explained
2. **CSS Variables**: Easy color/size changes
3. **Organized Structure**: Clear file organization
4. **Responsive Design**: Works on all devices
5. **No Build Process**: Simple HTML/CSS only

### Next Steps (Optional)
1. Add JavaScript for interactive features
2. Implement contact form with backend
3. Add blog section with CMS
4. Integrate with analytics
5. Add more animations with GSAP

## 🎨 Design Credits
- Inspired by [Brittany Chiang's Portfolio](https://brittanychiang.com)
- Color palette: Navy blue with cyan accents
- Typography: Modern sans-serif fonts
- Layout: Clean, minimal design

## 🆘 Troubleshooting

### Common Issues:
1. **Images not loading**: Check file paths and names
2. **CSS not applying**: Verify CSS file path in HTML
3. **Fonts not showing**: Add Google Fonts link to HTML
4. **Mobile not responsive**: Check viewport meta tag

### Need Help?
- Review the detailed comments in both HTML and CSS files
- Check browser developer tools for errors
- Validate your HTML at [W3C Validator](https://validator.w3.org)

## 📧 Support
If you need help customizing this template:
1. Read through all comments first
2. Check browser console for errors
3. Validate your HTML and CSS
4. Test on multiple devices/browsers

Happy coding! 🚀