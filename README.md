# ProfitPerItem Landing Page

A landing page for ProfitPerItem - a tool for UK resellers to track item-level profits.

## Features

- Responsive design using Tailwind CSS
- Netlify Forms integration for early access signups
- Mobile-first approach

## Deployment to Netlify via GitHub

### Prerequisites

1. A GitHub account
2. A Netlify account (free tier works)

### Steps

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Connect to Netlify:**
   - Go to [Netlify](https://app.netlify.com)
   - Click "Add new site" → "Import an existing project"
   - Connect your GitHub account and select this repository
   - Netlify will auto-detect settings:
     - Build command: (leave empty or use `echo 'No build step required'`)
     - Publish directory: `.` (root)
   - Click "Deploy site"

3. **Form Submissions:**
   - Form submissions will appear in your Netlify dashboard under "Forms"
   - You can set up email notifications in Netlify settings
   - Free tier includes 100 submissions/month

4. **Custom Domain (Optional):**
   - Go to Site settings → Domain management
   - Add your custom domain

## Local Development

Simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Form Configuration

The form uses Netlify Forms. To view submissions:
- Go to your Netlify dashboard
- Navigate to Forms → Your form name ("early-access")
- View submissions or set up email notifications

## License

MIT

