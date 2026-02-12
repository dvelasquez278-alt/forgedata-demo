# ForgeData MVP Prototype - Deployment Instructions

## ✅ Your prototype is ready!

You now have:
- `index.html` - The main prototype file
- `images/` folder with 3 UI mockup images
  - `feed-screen.png`
  - `cve-detail-screen.png`
  - `rule-detail-screen.png`

**Important**: You need BOTH the `index.html` file AND the `images/` folder for deployment!

## 🚀 Deployment Options

### Option 1: Use the PUBLISH Tab (Recommended)
1. Click the **"Publish"** tab at the top of this interface
2. Click **"Deploy"** or **"Publish to Web"**
3. You'll get a live URL instantly
4. Share that URL with VCs

### Option 2: Netlify Drop (Manual)
If Publish tab doesn't work:

1. **Download ALL files** from this project:
   - `index.html`
   - The entire `images/` folder with all 3 PNG files
2. **Keep them in the same folder structure** on your computer
3. Go to: https://app.netlify.com/drop
4. **Drag the ENTIRE FOLDER** (containing index.html + images/) onto Netlify
5. Wait 5-10 seconds
6. You'll get a URL like: `https://YOUR-SITE.netlify.app`

**Important**: Drag the whole folder, not just index.html!

### Option 3: GitHub Pages
1. Create a new repo on GitHub
2. Upload just `index.html`
3. Go to Settings → Pages
4. Select main branch
5. Get your `https://yourusername.github.io/repo-name` URL

### Option 4: Test Locally First
1. Download `index.html`
2. Double-click it to open in your browser
3. It should work perfectly offline
4. Once verified, deploy using Option 1 or 2

## 🔧 Troubleshooting

### "Broken link error" on Netlify?
This means Netlify couldn't access the file. Try:
1. Make sure you're only dragging `index.html` (not a folder)
2. Rename it to exactly `index.html` (lowercase)
3. Try https://app.netlify.com/drop again
4. OR use the Publish tab instead

### Images not loading?
The prototype uses these CDN URLs for images:
- https://www.genspark.ai/api/files/s/Mle9Lo0I?cache_control=3600
- https://www.genspark.ai/api/files/s/SeonHFMD?cache_control=3600  
- https://www.genspark.ai/api/files/s/4METo2wi?cache_control=3600

These should work from any deployed URL.

### Styling looks broken?
If the dark theme isn't showing:
1. Open browser console (F12)
2. Check for any errors
3. Verify the `<style>` tag is present in the HTML
4. Try clearing your browser cache

## 📱 What VCs Will See

When you share the deployed URL, they'll see:
- ✅ Professional dark-themed cybersecurity interface
- ✅ ForgeData branding with logo
- ✅ **Factory Activity Widget** showing "Last factory run" and "Coverage tests today"
- ✅ Clickable feed → CVE detail → Rule detail flow
- ✅ Realistic loading states and toast notifications
- ✅ Numbers that update every 30 seconds

## 🎬 Demo Flow

1. **Start on Feed**: Click any row in the threat feed table
2. **CVE Detail opens**: Point out the factory widget, then click a pack tile (Sigma/YARA/KQL)
3. **Rule Detail shows**: Show copy/download/push buttons, click them to see toast notifications
4. **Navigate back**: Use "Back to..." links or top nav

## 💡 Pro Tips

- The factory widget updates every 30 seconds during your demo
- Keep the demo open for 1-2 minutes before presenting so numbers update once
- Practice clicking through 2-3 times before your pitch
- Point out "Last factory run: 2h ago" early to establish operational credibility

## 📞 Need Help?

If deployment still fails:
1. Try the **Publish** tab first (easiest)
2. Share the specific error message
3. Take a screenshot of what you see
4. I can provide alternative deployment methods

---

**Quick Start**: Click the **Publish** tab now! 🚀
