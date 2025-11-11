# Personal Portfolio Website

A modern, professional, and mobile-friendly portfolio website for a Full Stack Software Developer specializing in Java Spring Boot and .NET Core.

## Features

- ✨ **Modern Design**: Clean, minimalist, and professional layout
- 🌓 **Dark Mode**: Toggle between light and dark themes
- 📱 **Fully Responsive**: Mobile-first design that works on all devices
- ⚡ **Smooth Animations**: Fade-in effects and smooth scrolling
- ⌨️ **Typing Animation**: Dynamic typing effect showcasing technical skills
- 🎯 **SEO Optimized**: Meta tags and semantic HTML for better search indexing

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styles and animations
- **JavaScript**: Interactive features and animations
- **TailwindCSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icons
- **Google Fonts**: Poppins & Inter fonts

## File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/
    ├── profile.jpg     # Profile photo (add your image)
    ├── resume.pdf      # Resume PDF (add your resume)
    └── README.md       # Assets documentation
```

## Setup Instructions

1. **Add Your Assets**:
   - Place your professional profile photo in `assets/profile.jpg` (recommended: 800x800px, square format)
   - Place your resume PDF in `assets/resume.pdf`

2. **Customize Content** (if needed):
   - Update project GitHub/demo links in the Projects section
   - Modify any personal information as needed

3. **Open the Website**:
   - Simply open `index.html` in your web browser
   - Or use a local server (e.g., `python -m http.server` or Live Server extension)

## Sections

1. **Home**: Landing page with name, title, typing animation, and call-to-action buttons
2. **About Me**: Professional summary and key highlights
3. **Technical Skills**: Organized skill cards with progress bars and tags
4. **Projects**: Interactive project cards with descriptions and tech stacks
5. **Experience & Education**: Professional experience, education, and certifications
6. **Contact**: Contact information with social media links

## Features Explained

### Typing Animation
The home section features a dynamic typing animation that cycles through technical skills:
- Java • Spring Boot • .NET Core • C# • REST API • MySQL • SQL Server • Angular • Electron • JWT • API Design • Git • Postman

### Dark Mode
- Toggle button in the navigation bar
- Preference is saved in localStorage
- Smooth transition between themes

### Smooth Scrolling
- All navigation links use smooth scrolling
- Active section highlighting in navigation
- Mobile menu auto-closes on link click

### Responsive Design
- Mobile-first approach
- Breakpoints: sm (640px), md (768px), lg (1024px)
- Optimized for all screen sizes

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Customization

### Colors
The website uses TailwindCSS color classes. To change the accent color (currently blue), search and replace:
- `blue-600` → your color
- `blue-400` → lighter shade of your color
- `blue-700` → darker shade of your color

### Fonts
Currently using Inter and Poppins from Google Fonts. To change, modify the Google Fonts link in the `<head>` section.

## Deployment

You can deploy this portfolio to:
- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your repository
- **Railway/Render**: As mentioned in your skills

## Notes

- Ensure all image paths are correct
- Test the resume download link
- Verify all external links (GitHub, LinkedIn) are working
- Optimize images for web to ensure fast loading

## License

This portfolio template is free to use and modify for personal use.

---

**Built with ❤️ for showcasing your professional journey**

