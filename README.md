# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- 📱 Fully responsive design
- 🎨 Modern and clean UI
- ⚡ Smooth animations and transitions
- 🔗 Easy to customize
- 🚀 Ready for GitHub Pages deployment

## Sections

- **Home/Hero**: Eye-catching introduction
- **About**: Personal information and introduction
- **Projects**: Showcase your work
- **Skills**: Display your technical skills
- **Contact**: Contact information and links

## How to Deploy to GitHub Pages

1. **Create a new repository on GitHub**
   - Go to GitHub and create a new repository
   - Name it `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Make it public

2. **Initialize Git and push your code**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"

4. **Access your site**
   - Your portfolio will be live at `https://yourusername.github.io`
   - It may take a few minutes for the site to go live

## Customization

### Update Personal Information
- Edit `index.html` to replace:
  - "Your Name" with your actual name
  - Email, GitHub, and LinkedIn links in the contact section
  - Project descriptions and links

### Change Colors
- Edit `styles.css` and modify the CSS variables in the `:root` section:
  ```css
  :root {
      --primary-color: #6366f1;
      --secondary-color: #8b5cf6;
      /* ... other colors */
  }
  ```

### Add Your Projects
- Replace placeholder images in the projects section
- Update project titles, descriptions, and links

### Add Your Skills
- Update the skills section with your actual technologies and tools

## Local Development

To view your portfolio locally:
1. Open `index.html` in your web browser
2. Or use a local server (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

## License

Feel free to use this template for your own portfolio!
