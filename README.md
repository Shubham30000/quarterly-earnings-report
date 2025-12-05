<<<<<<< HEAD
# 📊 Quarterly Earnings Report - Interactive Presentation

An interactive web-based presentation built with RevealJS for showcasing Q4 2024 financial results. This project demonstrates modern presentation capabilities with animations, code highlighting, mathematical formulas, and speaker notes.

## 🌐 Live Demo

**View the presentation:** [https://Shubham30000.github.io/quarterly-earnings-report/](https://Shubham30000.github.io/quarterly-earnings-report/)

> Replace `YOUR-USERNAME` with your actual GitHub username

---

## 📋 Project Overview

This is an interactive HTML presentation created for a financial institution's quarterly earnings report. Unlike traditional PowerPoint presentations, this web-based solution offers:

- **Browser-based presentation** - No software installation required
- **Interactive elements** - Animated fragments and transitions
- **Code syntax highlighting** - Display algorithms and queries beautifully
- **Mathematical equations** - Render financial formulas with KaTeX
- **Speaker notes** - Hidden presenter guidance
- **Responsive design** - Works on desktop, tablet, and mobile
- **Keyboard navigation** - Professional presentation controls

---

## ✨ Features Implemented

### Required Features
- ✅ Email address displayed: `23f2005282@ds.study.iitm.ac.in`
- ✅ Markdown slides for easy content creation
- ✅ Animated fragments with fade effects
- ✅ Code syntax highlighting (Python, SQL)
- ✅ Mathematical equations (Sharpe Ratio, CAPM, VaR)
- ✅ Speaker notes on every slide
- ✅ Published on GitHub Pages

### Additional Features
- 🎨 Professional dark theme (Night theme)
- 🔢 Line-by-line code highlighting
- 📱 Responsive design
- ⌨️ Comprehensive keyboard shortcuts
- 🎯 Overview mode for navigation
- 📝 9 comprehensive slides covering financial topics

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and content |
| **CSS3** | Styling and animations |
| **JavaScript** | Interactivity and presentation logic |
| **RevealJS 4.5.0** | Presentation framework |
| **KaTeX** | Mathematical equation rendering |
| **Highlight.js** | Code syntax highlighting |
| **Markdown** | Simplified content writing |
| **GitHub Pages** | Free web hosting |

---

## 📂 Project Structure

```
quarterly-earnings-report/
│
├── README.md           # Project documentation (this file)
└── index.html          # Main presentation file
```

### File Breakdown

- **index.html**: Single-page application containing:
  - RevealJS framework integration via CDN
  - 9 slides with financial content
  - Custom CSS styling
  - Plugin initialization (Markdown, Highlight, Math, Notes)
  - Speaker notes for each slide

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Git installed on your computer
- GitHub account
- VS Code (recommended) or any text editor

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shubham30000/quarterly-earnings-report.git
   cd quarterly-earnings-report
   ```

2. **Open in VS Code**
   ```bash
   code .
   ```

3. **Preview locally** (Optional)
   - Install "Live Server" extension in VS Code
   - Right-click `index.html` → "Open with Live Server"
   - View at `http://127.0.0.1:5500`

4. **Make changes**
   - Edit `index.html`
   - Save and see changes in real-time (with Live Server)

---

## 📝 How to Use the Presentation

### Navigation

| Key | Action |
|-----|--------|
| `→` `↓` `Space` | Next slide |
| `←` `↑` | Previous slide |
| `F` | Enter fullscreen mode |
| `S` | Open speaker notes (separate window) |
| `O` | Overview mode (see all slides) |
| `ESC` | Exit overview/fullscreen |
| `B` or `.` | Pause (blank screen) |
| `?` | Show all keyboard shortcuts |

### Presenting Tips

1. **Press `S`** to open speaker notes window on a second screen
2. **Press `O`** to see an overview before starting
3. **Use arrow keys** for smooth navigation
4. **Press `F`** for professional fullscreen mode
5. Speaker notes show:
   - Current slide notes
   - Next slide preview
   - Timer and clock

---

## 📊 Presentation Content

### Slides Overview

1. **Title Slide** - Introduction with contact information
2. **Executive Summary** - Markdown slide with key highlights
3. **Key Financial Metrics** - Animated revenue and profit figures
4. **Risk Analysis** - Python code with syntax highlighting
5. **Portfolio Metrics** - Sharpe Ratio formula and calculation
6. **CAPM & VaR** - Capital Asset Pricing Model equations
7. **Data Analytics** - SQL query example
8. **Strategic Priorities** - Animated list of Q1 2025 goals
9. **Closing** - Thank you and contact information

### Topics Covered

- Revenue growth and profitability
- Risk management algorithms
- Portfolio performance metrics
- Financial formulas (Sharpe Ratio, CAPM, VaR)
- Data analytics implementation
- Strategic business initiatives

---

## 🎨 Customization Guide

### Change Theme

Replace the theme in line 11 of `index.html`:

```html
<!-- Current: Dark theme -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js@4.5.0/dist/theme/night.css">

<!-- Options: -->
<!-- White theme -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js@4.5.0/dist/theme/white.css">

<!-- Black theme -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js@4.5.0/dist/theme/black.css">

<!-- Other themes: beige, sky, serif, simple, solarized -->
```

### Add New Slides

Add between the `<div class="slides">` tags:

```html
<section>
    <h2>Your Slide Title</h2>
    <p>Your content here</p>
    <aside class="notes">
        Your speaker notes here
    </aside>
</section>
```

### Modify Colors

Edit the custom CSS in the `<style>` section (lines 14-31):

```css
.reveal .email {
    color: #42affa;  /* Change this color */
}

.reveal .metric {
    color: #42affa;  /* Change this color */
}
```

### Add Code Blocks

```html
<pre><code class="python" data-line-numbers>
def your_function():
    print("Your code here")
</code></pre>
```

Supported languages: `python`, `javascript`, `sql`, `java`, `cpp`, `html`, `css`, etc.

### Add Math Equations

Inline: `\(E = mc^2\)`

Block:
```html
\[
    \frac{a}{b} = \frac{c}{d}
\]
```

---

## 🚢 Deployment

### Deploy to GitHub Pages

1. **Push your code to GitHub**
   ```bash
   git add .
   git commit -m "Update presentation"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" in sidebar
   - Under "Source": Select `main` branch and `/ (root)` folder
   - Click "Save"

3. **Wait for deployment**
   - GitHub will build and deploy (1-2 minutes)
   - Visit: `https://YOUR-USERNAME.github.io/quarterly-earnings-report/`

4. **Update with cache bypass**
   - After changes, add version parameter: `?v=2`, `?v=3`, etc.
   - Example: `https://YOUR-USERNAME.github.io/quarterly-earnings-report/?v=2`

---

## 🔧 Troubleshooting

### Presentation Not Loading

**Problem**: 404 error or blank page

**Solutions**:
- Wait 2-3 minutes after enabling GitHub Pages
- Ensure file is named exactly `index.html` (case-sensitive)
- Check that repository is set to Public
- Verify GitHub Pages is enabled in Settings → Pages

### Math Equations Not Rendering

**Problem**: Equations show as plain text

**Solutions**:
- Already included: KaTeX library loads from CDN
- Check browser console (F12) for errors
- Ensure internet connection (needs to load external libraries)

### Code Not Highlighted

**Problem**: Code appears without colors

**Solutions**:
- Already included: Highlight.js plugin enabled
- Verify language class is correct: `class="python"`
- Check browser console for plugin loading errors

### Changes Not Appearing

**Problem**: Edits don't show on live site

**Solutions**:
- Wait 1-2 minutes for GitHub Pages to rebuild
- Clear browser cache: `Ctrl + Shift + R` (hard refresh)
- Add version parameter to URL: `?v=2`
- Check commit was pushed: `git log` to verify

### Speaker Notes Not Opening

**Problem**: Pressing 'S' doesn't open notes window

**Solutions**:
- Allow pop-ups in browser settings
- Already included: Notes plugin is loaded
- Try in a different browser
- Check browser console for errors

---

## 📚 Resources & Documentation

### Official Documentation
- [RevealJS Documentation](https://revealjs.com/)
- [RevealJS GitHub](https://github.com/hakimel/reveal.js)
- [GitHub Pages Guide](https://docs.github.com/en/pages)

### Learning Resources
- [Markdown Guide](https://www.markdownguide.org/)
- [KaTeX Supported Functions](https://katex.org/docs/supported.html)
- [Highlight.js Languages](https://highlightjs.org/static/demo/)

### Related Projects
- [RevealJS Examples](https://github.com/hakimel/reveal.js/wiki/Example-Presentations)
- [RevealJS Themes](https://github.com/hakimel/reveal.js/tree/master/css/theme)

---

## 🤝 Contributing

This is a personal academic project, but suggestions are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m "Add feature"`
4. Push to branch: `git push origin feature-name`
5. Open a Pull Request

---

## 📄 License

This project is created for educational purposes as part of coursework at IIT Madras.

**RevealJS** is licensed under the MIT License.

---

## 👤 Author

**Student Email**: 23f2005282@ds.study.iitm.ac.in

**Institution**: Indian Institute of Technology Madras (IIT Madras)

**Course**: Data Science Program

**Project**: Interactive Technical Report with RevealJS

---

## 🙏 Acknowledgments

- **RevealJS** by Hakim El Hattab - Presentation framework
- **KaTeX** - Math rendering library
- **Highlight.js** - Code syntax highlighting
- **GitHub Pages** - Free hosting platform
- **IIT Madras** - Educational institution

---

## 📌 Project Status

✅ **Completed** - All requirements implemented

### Checklist
- [x] Email address included
- [x] Markdown slides
- [x] Animated fragments
- [x] Code syntax highlighting (Python, SQL)
- [x] Mathematical equations
- [x] Speaker notes
- [x] Deployed on GitHub Pages
- [x] Professional theme and styling
- [x] Comprehensive documentation

---

## 🔮 Future Enhancements

Potential improvements for future versions:

- [ ] Add interactive charts with Chart.js
- [ ] Include live data visualizations with D3.js
- [ ] Add video embeds for demonstrations
- [ ] Create custom theme with company branding
- [ ] Add audio narration for automated presentations
- [ ] Include print-to-PDF functionality
- [ ] Add multilingual support
- [ ] Create mobile-optimized version

---

## 📞 Support

For questions or issues:

1. **Email**: 23f2005282@ds.study.iitm.ac.in
2. **GitHub Issues**: Open an issue in this repository
3. **RevealJS Community**: [GitHub Discussions](https://github.com/hakimel/reveal.js/discussions)

---

## 📊 Project Statistics

- **Total Slides**: 9
- **Code Examples**: 3 (Python, SQL)
- **Math Equations**: 3 formulas
- **Technologies Used**: 8
- **Lines of Code**: ~300
- **Development Time**: 2-3 hours

---

**Last Updated**: December 2025

**Version**: 1.0.0

---

Made with ❤️ for IIT Madras Data Science Program
=======
# quarterly-earnings-report
>>>>>>> 64b7694e9e481b6ebb68536223a7640ec380edb5
