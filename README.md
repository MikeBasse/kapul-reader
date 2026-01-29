# 🐾 Kapul Reader

**Read. Understand. Learn.**

An AI-powered reading and learning app that combines document reading with intelligent tutoring. Select any text to get instant explanations, solve problems step-by-step, and quiz yourself on what you've read.

![Kapul Reader Preview](https://via.placeholder.com/800x400/0a0a0f/FBBF24?text=Kapul+Reader)

---

## 🚀 Deploy to Vercel (5 Minutes)

### Option A: Deploy with GitHub (Recommended)

**Step 1: Create a GitHub account** (skip if you have one)
- Go to [github.com](https://github.com)
- Click "Sign up" and follow the steps

**Step 2: Create a new repository**
1. Click the "+" icon in the top right → "New repository"
2. Name it `kapul-reader`
3. Keep it Public
4. Click "Create repository"

**Step 3: Upload these files**
1. On your new repository page, click "uploading an existing file"
2. Drag and drop ALL files from this folder:
   - `package.json`
   - `vite.config.js`
   - `vercel.json`
   - `index.html`
   - `.gitignore`
   - `src/` folder (with `main.jsx` and `App.jsx` inside)
3. Click "Commit changes"

**Step 4: Deploy to Vercel**
1. Go to [vercel.com](https://vercel.com)
2. Click "Sign Up" → "Continue with GitHub"
3. Authorize Vercel to access your GitHub
4. Click "Add New Project"
5. Find `kapul-reader` in the list and click "Import"
6. Keep all default settings
7. Click "Deploy"
8. Wait 1-2 minutes...
9. 🎉 Your app is live! Copy the URL (like `kapul-reader.vercel.app`)

---

### Option B: Deploy without GitHub (Direct Upload)

**Step 1: Install Vercel CLI**
```bash
npm install -g vercel
```

**Step 2: Navigate to project folder**
```bash
cd kapul-reader-deploy
```

**Step 3: Deploy**
```bash
vercel
```

Follow the prompts:
- Log in to Vercel (it will open your browser)
- Project name: `kapul-reader`
- Keep defaults for everything else

Your app will be live in ~1 minute!

---

## 📱 Testing the App

Once deployed, your app will be available at a URL like:
```
https://kapul-reader.vercel.app
```

**Share this link with your WhatsApp group!**

### Features to Test:

1. **Text Selection → AI Explain**
   - Select any text in the document
   - Click "Explain" for a simplified explanation

2. **Problem Solving**
   - Select a math problem
   - Click "Solve" for step-by-step solution

3. **Highlighting**
   - Select text and click "Highlight"
   - View saved highlights in the Study tab

4. **Quiz Mode**
   - Click "Quiz me on this chapter"
   - Test your understanding

5. **Library & Study Dashboard**
   - Explore the Library tab for book collection
   - Check Study tab for progress tracking

---

## 📝 Collecting Feedback

Create a Google Form with these questions:

1. **Ease of Use** (1-5 scale)
   "How easy was it to select text and get an explanation?"

2. **Explanation Quality** (1-5 scale)
   "Were the AI explanations helpful and clear?"

3. **Would You Use This?** (Yes/No/Maybe)
   "Would you use Kapul Reader instead of separate reader + tutor apps?"

4. **Missing Features** (Open text)
   "What's the #1 feature you wish it had?"

5. **Device Used** (Multiple choice)
   "What device did you test on?" - Phone / Tablet / Computer

6. **Open Feedback** (Open text)
   "Any other comments or suggestions?"

---

## 🔧 Local Development

If you want to make changes locally:

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

---

## 📁 Project Structure

```
kapul-reader-deploy/
├── index.html          # HTML entry point
├── package.json        # Dependencies and scripts
├── vite.config.js      # Vite build configuration
├── vercel.json         # Vercel deployment settings
├── .gitignore          # Git ignore rules
├── README.md           # This file
└── src/
    ├── main.jsx        # React entry point
    └── App.jsx         # Main Kapul Reader component
```

---

## 🐾 About Kapul

"Kapul" means "Cuscus" in Tok Pisin — a cute, intelligent marsupial native to Papua New Guinea. Just like the kapul is curious and resourceful, this app helps you explore and understand any reading material!

---

## 📄 License

MIT License - Feel free to modify and use for your own projects.

---

**Built with ❤️ for the Kapul Reading Group**
