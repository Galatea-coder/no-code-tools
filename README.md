# Non-Developer App Building: Complete Tools Landscape

An interactive guide covering 5 categories and 30+ tools for building applications without traditional coding — from no-code platforms to AI agent frameworks.

## 🚀 Quick Deploy to GitHub Pages

### Option 1: Fastest Method (GitHub Web Interface)

1. **Create a new repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `app-building-guide` or `yourname.github.io` (for a personal site)
   - Make it **Public**
   - Check "Add a README file"
   - Click **Create repository**

2. **Upload the file**
   - Click **Add file** → **Upload files**
   - Drag and drop `index.html`
   - Click **Commit changes**

3. **Enable GitHub Pages**
   - Go to **Settings** → **Pages** (in left sidebar)
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your site** (within 1-2 minutes)
   - Your site will be live at: `https://yourusername.github.io/repository-name/`

---

### Option 2: Git Command Line

```bash
# Clone your repo (after creating it on GitHub)
git clone https://github.com/yourusername/app-building-guide.git
cd app-building-guide

# Copy the index.html file here
cp /path/to/index.html .

# Push to GitHub
git add index.html
git commit -m "Add app building guide"
git push origin main

# Then enable GitHub Pages in Settings → Pages
```

---

### Option 3: GitHub CLI

```bash
# Create repo and deploy in one go
gh repo create app-building-guide --public --clone
cd app-building-guide
cp /path/to/index.html .
git add index.html
git commit -m "Add app building guide"
git push origin main

# Enable pages
gh api repos/{owner}/{repo}/pages -X POST -f source='{"branch":"main","path":"/"}'
```

---

## 📁 What's Included

### `index.html`
A single, self-contained HTML file with:
- **5 Categories** on the complexity → control spectrum
- **30+ Tools** with detailed information for each
- **Use Cases** — specific examples of what you can build
- **Sample Projects** — concrete project ideas with features
- **Resources** — documentation, courses, communities for each tool
- **Quick Reference Table** — "if you want to X, use Y" guide
- **Vibe Coding vs Proper AI-Assisted Development** comparison
- **Context Engineering Tools** reference

### No Build Step Required
- Uses React via CDN (no npm install needed)
- All styling is inline (no CSS files)
- Works as a static file anywhere

---

## 🔧 Customization

### Adding Your Branding
Edit the `<head>` section to update:
```html
<title>Your Custom Title</title>
<meta property="og:title" content="Your Title">
<meta property="og:description" content="Your description">
```

### Adding Your LinkedIn/Contact
Find the footer section and update:
```html
<p>Questions? Connect on <a href="https://linkedin.com/in/yourprofile">LinkedIn</a></p>
```

### Adding Google Analytics
Add before `</head>`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

## 📊 Content Structure

### Categories Covered

| # | Category | Tools Included |
|---|----------|---------------|
| 1 | **No-Code Platforms** | Bubble, Softr, Glide, Webflow, Framer |
| 2 | **Low-Code / Automation** | Zapier, Make, n8n, Retool, Power Automate, AppSheet |
| 3 | **AI Agent Builders** | OpenAI GPTs, Lindy, Relevance AI, MindStudio, Botpress, Voiceflow |
| 4 | **AI-Assisted Coding** | Claude.ai, Cursor, Replit Agent, v0, Bolt.new, Claude Code, Lovable |
| 5 | **Agent SDKs & Frameworks** | Claude Agent SDK, LangChain, CrewAI, AutoGen, Haystack, Semantic Kernel |

### For Each Tool
- Description and category
- Pricing information
- 4 detailed use cases
- Sample project with features list
- 4-5 learning resources with descriptions
- Strengths and limitations
- Direct link to website

---

## 🔗 Sharing on LinkedIn

Once deployed, you can:

1. **Share the link directly** in a post or article
2. **Embed in a LinkedIn Article** — add the URL and LinkedIn will create a preview card
3. **Create a QR code** linking to your guide for presentations

### Suggested Post Format
```
I created an interactive guide for non-developers who want to build apps.

5 categories. 30+ tools. Detailed use cases.

From no-code platforms to AI agent frameworks — with specific examples of what you can build with each.

Check it out: [your-url]

#nocode #ai #buildinpublic #tooling
```

---

## 📝 License

Feel free to use, modify, and share this guide. Attribution appreciated but not required.

---

## 🙋 Questions?

Open an issue in this repository or connect with me on LinkedIn.
