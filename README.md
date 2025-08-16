# Mahdi Hassanzadeh - Personal Website

A modern, responsive personal website built with Jekyll and deployed on GitHub Pages. Features a clean design with dark/light mode toggle and professional contact links.

## 🌟 Features

- **Jekyll-powered**: Static site generator for easy maintenance
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Dark/Light Mode**: Manual theme toggle with persistent preferences
- **Modern UI**: Clean, professional design with smooth animations
- **Contact Integration**: Icon-based social links with hover effects
- **GitHub Pages Ready**: Optimized for automatic deployment

## 🚀 Live Site

Visit: [https://hassanzadehmahdi.github.io](https://hassanzadehmahdi.github.io)

## 🛠️ Technology Stack

- **Jekyll 4.3.0** - Static site generator
- **SASS/SCSS** - Advanced CSS preprocessing
- **GitHub Pages** - Hosting and deployment
- **Vanilla JavaScript** - Interactive features
- **SVG Icons** - Scalable vector graphics

## 📁 Project Structure

```
hassanzadehmahdi_github_io/
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page layouts
│   └── default.html     # Main layout template
├── _includes/           # Reusable components
│   ├── header.html      # Site header with navigation
│   └── footer.html      # Site footer
├── _sass/               # SASS stylesheets
│   └── main.scss        # Main styles
├── assets/              # Static assets
│   ├── css/             # Compiled CSS
│   └── mahdi-hassanzadeh-resume.pdf
├── index.html           # Homepage content
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## 🎨 Customization

### Site Configuration
Edit `_config.yml` to update:
- Site title and description
- Contact information (email, GitHub, LinkedIn)
- Social media usernames

### Content Updates
- **Homepage**: Edit `index.html` for main content
- **Styling**: Modify `_sass/main.scss` for design changes
- **Layout**: Update `_layouts/default.html` for structural changes
- **Components**: Edit files in `_includes/` for reusable elements

### Adding New Pages
1. Create new `.html` or `.md` files in the root directory
2. Add front matter with layout specification
3. Jekyll will automatically generate the pages

## 🚀 Local Development

### Prerequisites
- Ruby 2.6+ 
- Bundler gem

### Setup
```bash
# Install dependencies
bundle install

# Serve locally (optional)
bundle exec jekyll serve
# Site will be available at http://localhost:4000
```

## 📦 Deployment

The site is automatically deployed via GitHub Pages:

1. Push changes to the `main` branch
2. GitHub Pages automatically builds and deploys
3. Updates are live within a few minutes

## 🎯 Key Features Explained

### Theme Toggle
- Manual light/dark mode switching
- Persistent preferences using localStorage
- Respects system preferences by default
- Smooth transitions between themes

### Contact Section
- Icon-based social links
- Platform-specific hover effects
- Responsive design for mobile
- Professional visual hierarchy

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Optimized typography scaling
- Touch-friendly interactions

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

**Built with ❤️ using Jekyll and GitHub Pages**
