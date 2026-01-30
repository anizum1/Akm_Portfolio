# 🚀 QUICK START GUIDE - Upload to GitHub in 5 Minutes!

## ✅ What You Have

**File:** `akm-portfolio-github.zip` (40 MB)

**Contains:**
- ✅ Website with organized folder structure
- ✅ 17 Cisco lab files (.pkt) in `cisco-labs/` folder
- ✅ 6 Presentations (.pptx/.pptm) in `presentations/` folder
- ✅ All images in `assets/images/` folder
- ✅ All PDFs in `assets/docs/` folder
- ✅ Comprehensive README.md
- ✅ Main website already renamed to `index.html`

---

## 📦 Step 1: Extract the ZIP File

1. Download `akm-portfolio-github.zip`
2. Extract/Unzip it to a folder
3. You'll see: `akm-portfolio/` folder

Inside the folder:
```
akm-portfolio/
├── index.html              ← Main website (already renamed!)
├── README.md               ← GitHub documentation
├── assets/                 ← Images & PDFs
│   ├── images/            (5 PNG files)
│   └── docs/              (2 PDF files)
├── cisco-labs/            ← 17 Packet Tracer labs
└── presentations/         ← 6 PowerPoint files
```

---

## 🌐 Step 2: Upload to GitHub

### **Option A: Using GitHub Website (Easiest)**

1. **Create Repository**
   - Go to https://github.com/new
   - Repository name: `cybersecurity-portfolio` or `akm-portfolio`
   - Make it **PUBLIC**
   - **Don't check** "Initialize with README" (you already have one)
   - Click "Create repository"

2. **Upload Files**
   - Click "uploading an existing file"
   - Open the extracted `akm-portfolio/` folder
   - **Drag ALL files and folders** into GitHub
   - **Important:** Upload the folder contents, not the folder itself
   - Commit message: "Initial portfolio upload with organized structure"
   - Click "Commit changes"

3. **Verify Structure**
   Your repo should show:
   ```
   ✓ index.html (in root)
   ✓ README.md (in root)
   ✓ assets/ (folder)
   ✓ cisco-labs/ (folder)
   ✓ presentations/ (folder)
   ```

### **Option B: Using Git Command Line**

```bash
# Create and navigate to your repository
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME

# Copy all files from extracted akm-portfolio folder
cp -r /path/to/extracted/akm-portfolio/* .

# Add, commit, and push
git add .
git commit -m "Initial portfolio with organized folder structure"
git push origin main
```

---

## 🎯 Step 3: Enable GitHub Pages

1. **Go to Settings**
   - In your repository, click "Settings" tab

2. **Navigate to Pages**
   - Look for "Pages" in the left sidebar
   - Click it

3. **Configure Pages**
   - Source: "Deploy from a branch"
   - Branch: `main`
   - Folder: `/ (root)`
   - Click "Save"

4. **Wait 2-3 Minutes**
   - GitHub will build your site
   - Refresh the Pages settings page
   - You'll see: "Your site is live at https://YOUR-USERNAME.github.io/REPO-NAME/"

---

## ✅ Step 4: Test Your Portfolio

1. **Open Your Site**
   - URL: `https://YOUR-USERNAME.github.io/REPO-NAME/`

2. **Test Login**
   - Password: `password`
   - You should see the boot sequence
   - Desktop should load with 12 icons

3. **Test Features**
   - ✅ Desktop icons work
   - ✅ Applications menu works
   - ✅ Terminal opens and commands work
   - ✅ Cisco Labs folder shows 17 labs
   - ✅ Presentations folder shows 6 presentations
   - ✅ Images load correctly
   - ✅ Certificates open in PDF viewer
   - ✅ Resume downloads

4. **Test Downloads**
   - Click a Cisco lab → Should download .pkt file
   - Click a presentation → Should download .pptx/.pptm file
   - Click Resume → Should download PDF

---

## 📂 Understanding the Folder Structure

### **Why Folders?**
✅ **Professional** - Clean, organized repository
✅ **Maintainable** - Easy to add/update files
✅ **Scalable** - Can grow without getting messy
✅ **Standard** - Follows best practices

### **How It Works:**
The website (`index.html`) references files using folder paths:
- Images: `assets/images/wallpaper-code.png`
- PDFs: `assets/docs/Certs.pdf`
- Labs: `cisco-labs/MIDTERM-Demo-Lab.pkt`
- Presentations: `presentations/Oracle-Health-Data-Breach-2025.pptx`

**Important:** All files MUST maintain this structure. Don't move files out of their folders!

---

## 🔧 Common Issues & Solutions

### **Issue: Images Not Loading**
**Cause:** Files moved out of `assets/images/` folder
**Fix:** Put images back in `assets/images/`

### **Issue: PDFs Not Opening**
**Cause:** PDFs not in `assets/docs/` folder
**Fix:** Put PDFs back in `assets/docs/`

### **Issue: GitHub Pages Not Working**
**Cause:** Repository is private or Pages not enabled
**Fix:** 
1. Make repository PUBLIC
2. Enable Pages in Settings
3. Wait 3-5 minutes
4. Hard refresh browser (Ctrl+Shift+R)

### **Issue: Files Not Downloading**
**Cause:** Files not uploaded to correct folder
**Fix:** Verify folder structure matches the ZIP file

---

## 📝 What to Do Next

### **1. Customize Your Portfolio**
Edit `README.md`:
- Replace `YOUR-USERNAME` with your GitHub username
- Add your actual GitHub Pages URL

### **2. Share Your Portfolio**
- **LinkedIn:** Add to featured section and profile
- **Resume:** Add portfolio URL
- **Job Applications:** Include in cover letters
- **Email Signature:** Add portfolio link

### **3. Keep It Updated**
- Add new projects as you complete them
- Upload additional certifications
- Include new presentations
- Update skills and experience

---

## 🎉 Success Checklist

- [ ] ZIP file extracted
- [ ] GitHub repository created (PUBLIC)
- [ ] All files and folders uploaded
- [ ] Folder structure intact:
  - [ ] `index.html` in root
  - [ ] `assets/` folder with subfolders
  - [ ] `cisco-labs/` folder with 17 files
  - [ ] `presentations/` folder with 6 files
  - [ ] `README.md` in root
- [ ] GitHub Pages enabled
- [ ] Site loads at GitHub Pages URL
- [ ] Login works (password: `password`)
- [ ] Desktop displays correctly
- [ ] All features tested and working
- [ ] Files download correctly

---

## 📧 Support

If you run into any issues:

1. **Check folder structure** - Most issues come from files in wrong location
2. **Wait 3-5 minutes** after enabling Pages - GitHub needs time to build
3. **Hard refresh** your browser (Ctrl+Shift+R or Cmd+Shift+R)
4. **Check repository is PUBLIC** - Private repos don't work with free Pages

---

## 🎯 Your Portfolio URL

Once everything is set up, share:

```
https://YOUR-USERNAME.github.io/REPO-NAME/

Password: password
```

**Example:**
```
https://anizum1.github.io/cybersecurity-portfolio/

Password: password
```

---

## 🌟 Why This Portfolio Rocks

✨ **Unique Design** - Linux-style interactive interface (nobody else has this!)  
✨ **Organized** - Professional folder structure  
✨ **Complete** - Projects, labs, presentations, certifications  
✨ **Downloadable** - Recruiters can download your work  
✨ **Impressive** - Shows technical skill AND creativity  
✨ **Professional** - Ready for job applications  

---

## 💼 Using in Job Applications

**Email Template:**
```
Dear [Hiring Manager],

I'm excited to apply for the [Position] role. I've created an 
interactive portfolio showcasing my cybersecurity work, including:

• 18 security projects (Python, OSINT, web security)
• 17 Cisco CCNA network labs
• 6 professional security presentations
• Multiple certifications including NSA CAE-CD and CCNA

Portfolio: https://YOUR-USERNAME.github.io/REPO-NAME/
Password: password

Looking forward to discussing how my skills can contribute to your team.

Best regards,
Akm Nizum
```

---

**🚀 You're ready to impress recruiters! Good luck with your job search!**

---

*Created with ❤️ for Akm Nizum's cybersecurity career*
*Questions? Review the main README.md in your repository*
