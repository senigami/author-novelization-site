# Author Novelization & Publishing Enablement Site

A static website template for a service helping LitRPG/Fantasy authors publish their work. Built with semantic HTML, CSS3 (Variables, Flexbox, Grid), and Vanilla JS.

## Project Structure
```
/
├── index.html          # Homepage
├── services.html       # Services & Pricing
├── portfolio.html      # Portfolio / Case Studies
├── contact.html        # Contact Form
├── assets/
│   ├── css/
│   │   └── styles.css  # Main stylesheet
│   ├── js/
│   │   └── script.js   # Mobile nav & effects
│   └── images/         # Placeholder assets
```

## How to Run Locally

### Option 1: VS Code Live Server (Recommended)
1. Open this folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click on `index.html` and select **"Open with Live Server"**.
4. The site will open in your default browser at `http://127.0.0.1:5500`.

### Option 2: Python Simple HTTP Server
If you have Python installed:
1. Open a terminal in the project root.
2. Run: `python3 -m http.server`
3. Visit `http://localhost:8000` in your browser.

## Deployment to GitHub Pages

1. **Commit & Push**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   # Add your remote
   # git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   # git push -u origin main
   ```

2. **Enable Pages**:
   - Go to your repository on GitHub.
   - Go to **Settings** > **Pages**.
   - Under **Source**, select `main` branch and `/ (root)` folder.
   - Click **Save**.
   - Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`.

## Customization
- **Colors & Fonts**: Edit `assets/css/styles.css` `:root` variables.
- **Images**: Replace files in `assets/images/`.
- **Form**: Update the `action` attribute in `contact.html` with your real [Formspree](https://formspree.io) endpoint.
