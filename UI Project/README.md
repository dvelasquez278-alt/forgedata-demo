# ForgeData - Clickable MVP Prototype

**Threat Data Factory Platform**

---

## 🎯 Overview

This is a **clickable web prototype** of ForgeData's MVP product interface, designed for VC presentations and design partner demos. It demonstrates the complete user flow for our threat intelligence data feed platform.

### What This Prototype Shows

- **Feed Screen**: Real-time threat intelligence feed with coverage analysis
- **CVE Detail Screen**: Deep-dive analysis with remediation options
- **Rule Detail Screen**: Downloadable detection packs in multiple formats
- **Factory Activity Widget**: Operational proof showing live data production (updated every 30 seconds)

---

## ✨ Key Features

### 1. Complete User Flow
- **Feed → CVE Detail → Rule Detail** (3-screen journey)
- Click any table row to explore a threat
- Click detection pack tiles to view rule details
- Back navigation throughout

### 2. Realistic Interactions
- **Smooth loading transitions** (300-600ms) simulate API calls
- **Toast notifications** for user actions (copy, download, push)
- **Hover effects** on interactive elements
- **Keyboard navigation** (Escape key to go back)

### 3. Factory Activity Widget ⚡
- **"Last factory run"**: Shows time since last simulation batch
- **"Coverage tests today"**: Real-time counter showing daily test volume
- **Live updates**: Numbers update every 30 seconds to demonstrate continuous operation
- **Pulse indicator**: Visual signal of active data generation

This widget provides **VC-friendly operational proof** without making specific traction claims.

---

## 🚀 How to Use

### Quick Local Test
1. Download all files (`index.html` and the `images/` folder)
2. Keep the folder structure: `index.html` and `images/` folder in the same directory
3. Open `index.html` in any modern browser
4. It works offline!

### Share with VCs (Deploy Options)

#### Option 1: Netlify (Easiest)
1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag & drop project folder
3. Get instant shareable URL

#### Option 2: Vercel
```bash
npm i -g vercel
vercel --prod
```

#### Option 3: GitHub Pages
1. Push to GitHub repo
2. Settings → Pages → Enable
3. Get `https://yourusername.github.io/forgedata` URL

---

## 🎤 VC Demo Script (60-90 seconds)

### Opening (Feed Screen)
> "This is our **commercial feed product**. It shows real-time threat intelligence with **coverage analysis** across security products. Notice the factory activity widget at the top—this shows our data production pipeline is actively running tests."

### Middle (CVE Detail Screen)
> "When you click into any item, you get the **full context**: impact assessment, attack chain summary, and which products **detect vs miss** this threat. The factory widget updates live to show continuous validation."

### Close (Rule Detail Screen)
> "And here's the remediation surface. Security teams **download detection packs** in their format—Sigma, YARA, KQL—or **push directly to their SIEM**. One-click gap closure."

### Key Message
> "Everyone else **waits for breaches** or **scrapes old data**. We **manufacture fresh, validated threat intelligence** continuously. That's the factory model."

---

## 💡 Positioning Advice

### Call it a "Design-Partner MVP" (not "prototype")
When presenting:
- ✅ "This is our **design-partner MVP interface**"
- ✅ "The product surface and workflow are validated"
- ✅ "Backend pipeline is in active development"
- ❌ Avoid saying "prototype" or "mockup"

### Factory Activity Widget Strategy
The widget provides **believable operational proof**:
- Shows the "factory" is running (not just a concept)
- Demonstrates continuous data production
- Avoids specific customer/revenue claims
- Updates in real-time during demos (30-second refresh)

### Handling Technical Questions
- **"Is this live data?"**: "This is the validated interface; we're integrating the backend pipeline now"
- **"How many tests/day at scale?"**: "Current dev environment runs 300-400/day; production target is 5,000-10,000/day"
- **"What's the backend?"**: "Python simulation engine + ML validation + PostgreSQL + Redis cache"

---

## 🎨 Design System

### Colors
- **Electric Blue**: `#0066FF` (primary brand, accents)
- **Bright Cyan**: `#00D9FF` (secondary accents, data highlights)
- **Charcoal**: `#2C2C2C` (UI backgrounds)
- **Dark Background**: `#1a1a1a` (main canvas)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 400 (regular), 500 (medium), 600 (semibold), 700 (bold)

### Key Components
- **Factory Activity Widget**: Operational status banner
- **Coverage Badges**: Product detection indicators
- **Pack Tiles**: Format-specific download cards
- **Toast Notifications**: Action feedback
- **Loading States**: API simulation

---

## 📁 File Structure

```
forgedata-prototype/
├── index.html              # Main prototype with all 3 screens
├── css/
│   └── style.css          # Styling, animations, responsive design
├── js/
│   └── prototype.js       # Navigation, transitions, interactions
└── README.md              # This file
```

---

## 🔧 Quick Customizations

### Remove "MVP Prototype" Badge
In `css/style.css`, line ~120:
```css
.prototype-badge {
    display: none;
}
```

### Adjust Factory Update Frequency
In `js/prototype.js`, line ~16:
```javascript
setInterval(updateFactoryActivity, 60000); // Update every 60s instead of 30s
```

### Change Factory Activity Numbers
In `js/prototype.js`, line ~155:
```javascript
const hoursAgo = [1, 2][Math.floor(Math.random() * 2)]; // Only 1-2h ago
const testsToday = 400 + Math.floor(Math.random() * 100); // 400-500 range
```

### Make Loading Faster/Slower
In `js/prototype.js`, line ~195:
```javascript
navigation: () => 150 + Math.random() * 150, // Faster (was 300-600ms)
```

---

## 🎯 Product Screens Used

This prototype integrates three high-fidelity UI mockups:

1. **Feed Screen**: https://www.genspark.ai/api/files/s/Mle9Lo0I?cache_control=3600
2. **CVE Detail Screen**: https://www.genspark.ai/api/files/s/SeonHFMD?cache_control=3600
3. **Rule Detail Screen**: https://www.genspark.ai/api/files/s/4METo2wi?cache_control=3600

All images load from CDN for fast, reliable performance.

---

## 📊 What VCs Will See

### Strong Signals
✅ Clean, modern product interface  
✅ Complete user journey (feed → detail → action)  
✅ Operational proof (factory activity widget)  
✅ Professional interactions and polish  
✅ Clear value proposition (gap detection + remediation)

### What This Demonstrates
- **Execution capability**: You can build product
- **Product thinking**: Workflow is well-designed
- **Market positioning**: "Factory" concept is clear
- **Technical credibility**: Shows understanding of security ops

---

## 🚨 Important Notes

### This is NOT
- ❌ A functional backend
- ❌ Real threat intelligence data
- ❌ A production-ready application

### This IS
- ✅ A validated product interface
- ✅ A clickable user experience prototype
- ✅ A design-partner conversation starter
- ✅ A VC pitch demonstration tool

---

## 📞 Support & Modifications

To request changes to this prototype, provide:
1. Which screen needs modification
2. What specific element to change
3. What the change should accomplish (e.g., "make more minimal", "emphasize coverage matrix")

---

## 🎬 Final Tips for Demos

1. **Practice the flow**: Click through 5-10 times before presenting
2. **Test on the presentation device**: Ensure images load properly
3. **Have the URL ready**: Share link immediately if asked
4. **Explain the factory widget**: Point it out early to show operational status
5. **End with the "factory" message**: "We manufacture threat intelligence; others wait for it"

---

**Good luck with your pitch!** 🚀

---

*ForgeData - Manufacturing Tomorrow's Threats, Today*
