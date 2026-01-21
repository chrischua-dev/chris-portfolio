# Chris Chua - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my professional experience, skills, and projects in AI, drone technology, and systems engineering.

## 🚀 Live Demo

Visit: [your-domain.vercel.app](https://your-domain.vercel.app)

## ✨ Features

- **Modern Design**: Dark theme with gradient accents and animated background effects
- **Fully Responsive**: Looks great on desktop, tablet, and mobile devices
- **Smooth Animations**: Intersection Observer-based fade-in animations
- **Single Page**: Fast-loading static HTML with no build step required
- **SEO Optimized**: Meta tags and semantic HTML structure

## 📁 Project Structure

```
chris-portfolio/
├── index.html      # Main website file
└── README.md       # Documentation
```

## 🛠️ Local Development

Simply open `index.html` in your browser to preview the website locally.

```bash
# Using Python's built-in server
python -m http.server 8000

# Or using Node.js
npx serve .
```

Then visit `http://localhost:8000`

---

## 📦 Deployment Guide

### Step 1: Create a GitHub Repository

1. **Go to GitHub** and sign in to your account
2. Click the **"+"** button in the top right and select **"New repository"**
3. Fill in the details:
   - **Repository name**: `chris-portfolio` (or any name you prefer)
   - **Description**: "Personal portfolio website"
   - **Visibility**: Public (recommended for free Vercel hosting)
   - ✅ Check "Add a README file" (optional, we already have one)
4. Click **"Create repository"**

### Step 2: Upload Files to GitHub

#### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"uploading an existing file"** or **"Add file" > "Upload files"**
2. Drag and drop both `index.html` and `README.md` files
3. Add a commit message: "Initial portfolio website"
4. Click **"Commit changes"**

#### Option B: Using Git Command Line

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/chris-portfolio.git

# Navigate to the folder
cd chris-portfolio

# Copy your files into this folder, then:
git add .
git commit -m "Initial portfolio website"
git push origin main
```

### Step 3: Deploy to Vercel

1. **Go to [Vercel](https://vercel.com)** and sign up/sign in (use "Continue with GitHub" for easiest setup)

2. Click **"Add New..."** > **"Project"**

3. **Import your GitHub repository**:
   - Find and select `chris-portfolio` from your repository list
   - Click **"Import"**

4. **Configure the project**:
   - **Project Name**: `chris-portfolio` (or customize)
   - **Framework Preset**: Select **"Other"** (since this is static HTML)
   - **Root Directory**: Leave as `.` (default)
   - No build command or output directory needed for static HTML

5. Click **"Deploy"**

6. **Wait for deployment** (usually takes 30-60 seconds)

7. **Your site is live!** Vercel will provide a URL like:
   - `chris-portfolio.vercel.app`
   - Or `chris-portfolio-YOUR_USERNAME.vercel.app`

### Step 4: Custom Domain (Optional)

To use your own domain (e.g., `chrischua.dev`):

1. In Vercel dashboard, go to your project
2. Click **"Settings"** > **"Domains"**
3. Enter your custom domain and click **"Add"**
4. Vercel will show you DNS records to configure with your domain registrar
5. Add the records to your domain's DNS settings
6. Wait for DNS propagation (usually 5-30 minutes)

---

## 🔄 Making Updates

### Updating via GitHub

1. Edit files directly on GitHub:
   - Go to your repository
   - Click on `index.html`
   - Click the pencil icon (✏️) to edit
   - Make changes and commit

2. **Vercel automatically redeploys** when you push changes to GitHub!

### Updating via Git

```bash
# Make changes to your files locally
git add .
git commit -m "Update portfolio content"
git push origin main
```

Vercel will automatically detect the changes and redeploy.

---

## 🎨 Customization

### Colors
Edit the CSS variables in `index.html`:
```css
:root {
    --accent-cyan: #00d4ff;
    --accent-magenta: #ff0080;
    --accent-purple: #7b2dff;
    /* ... more colors */
}
```

### Content
Update the following sections in `index.html`:
- Hero section (name, tagline)
- About section (bio, stats)
- Experience timeline
- Skills grid
- Projects cards
- Education cards
- Contact links

### Adding More Projects
Copy and modify the project card template:
```html
<div class="project-card">
    <div class="project-image">🎯</div>
    <div class="project-content">
        <div class="project-tags">
            <span class="project-tag">Tag1</span>
            <span class="project-tag">Tag2</span>
        </div>
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-links">
            <a href="URL" target="_blank" class="project-link">View Code</a>
        </div>
    </div>
</div>
```

---

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Chris Chua**
- Email: chrischua82@gmail.com
- LinkedIn: [chris-chua-sg](https://sg.linkedin.com/in/chris-chua-sg)
- GitHub: [bamsby](https://github.com/bamsby)
