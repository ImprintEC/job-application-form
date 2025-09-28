# Job Application Form - Vercel Deployment

## Quick Deploy to Vercel

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and create a new repository
2. Name it: `job-application-form`
3. Upload these files:
   - `index.html`
   - `package.json` 
   - `vercel.json`
   - `README.md`

### Step 2: Deploy to Vercel
1. Go to [Vercel.com](https://vercel.com)
2. Click "Import Project"
3. Connect your GitHub repository
4. Click "Deploy" - that's it!

### Step 3: Configure Your Form
1. Open your deployed site
2. Edit the CONFIG section in `index.html`:
   ```javascript
   const CONFIG = {
       API_KEY: 'your_monday_api_key_here',
       BOARD_ID: '18058326311', 
       COMPANY_NAME: 'Your Company Name'
   };
