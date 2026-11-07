# FIT 360 CLUB

A modern, high-performance, dark-themed fitness club landing page featuring responsive design, interactive transformation comparison slider, fitness calculators (BMI & Daily Calorie needs), and smooth scroll animations.

---

## 🚀 Deploy to Vercel

This project is pre-configured and 100% ready for instant deployment on [Vercel](https://vercel.com).

### Option 1: Deploy with Vercel CLI (Fastest)

1. Open your terminal in this directory:
   ```bash
   cd d:\Github\Work\FIT360CLUB
   ```
2. Log in and deploy:
   ```bash
   npx vercel
   ```
   Follow the interactive prompts:
   - **Set up and deploy?** `Y`
   - **Which scope?** (Select your personal account or team)
   - **Link to existing project?** `N`
   - **What's your project's name?** `fit360club` (or press Enter)
   - **In which directory is your code located?** `./` (press Enter)
   - **Want to modify these settings?** `N`

3. To deploy directly to production:
   ```bash
   npx vercel --prod
   ```

---

### Option 2: Deploy with GitHub & Vercel Dashboard (Continuous Deployment)

1. Initialize git and commit your files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Ready for Vercel deployment"
   ```

2. Create a new repository on [GitHub](https://github.com/new) and push your code:
   ```bash
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
   git push -u origin main
   ```

3. Go to [Vercel Dashboard](https://vercel.com/new):
   - Click **"Add New..."** > **"Project"**
   - Choose your GitHub repository and click **Import**
   - Framework Preset: **Other** (detected automatically)
   - Root Directory: `./`
   - Click **Deploy**

Every push to your `main` branch will automatically trigger a new production deployment with instant edge propagation and free SSL!

---

## 🛠️ Project Structure

```text
FIT360CLUB/
├── 404.html             # Custom branded 404 error page
├── css/
│   └── style.css        # Custom scrollbar, swoop animations, text reveals
├── js/
│   └── main.js          # Interactive slider, calculators, mobile menu, intersection observers
├── favicon.svg          # High-resolution vector favicon
├── index.html           # Main landing page with Tailwind CDN & Lucide Icons
├── vercel.json          # Vercel configuration (clean URLs & security headers)
├── .vercelignore        # Files excluded from Vercel deployment builds
├── .gitignore           # Git ignore configuration
└── README.md            # Project documentation and deployment guide
```

---

## 💻 Local Preview

You can test the website locally using any static web server:

```bash
# Using npx serve:
npx serve .

# Or using Python:
python -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

