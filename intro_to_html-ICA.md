# Lesson 2: In-Class Assignments
## HTML Fundamentals & Version Control

---

## **Assignment 1: Create Your First Webpage** ⏰ 10 minutes

### **Objective**
Create a simple personal introduction page using HTML structure.

### **Setup Instructions**
1. **Create a new folder** for your project (e.g., "my-portfolio")
2. **Open the folder in VS Code** (File → Open Folder)
3. **Create a new HTML file:**
   - Right-click in the Explorer panel
   - Select "New File"
   - Name it `index.html`

### **Coding Instructions**
1. **Use the HTML boilerplate structure** (type `!` + Tab in VS Code for quick setup)
2. **Add these elements:**
   - Your name as the main heading (h1)
   - A paragraph about yourself
   - Your favorite hobby as a subheading (h2)
   - A paragraph about that hobby
3. **Test with Live Server** (right-click index.html → "Open with Live Server")

### **Starter Template**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Add meta tags and title here -->
</head>
<body>
    <!-- Add your name as h1 here -->
    <!-- Add paragraph about yourself here -->
    <!-- Add hobby as h2 here -->
    <!-- Add paragraph about hobby here -->
</body>
</html>
```

### **Success Criteria**
- [ ] Page displays correctly in browser
- [ ] All text is visible and properly structured
- [ ] No errors showing in VS Code
- [ ] Uses proper heading hierarchy (h1, h2)

### **Need Help?**
- Remember to use opening and closing tags: `<h1>Title</h1>`
- Check for typos in element names
- Make sure all tags are properly nested

---

## **Assignment 2: Build a Personal Profile Page** ⏰ 15 minutes

### **Objective**
Expand your webpage with semantic HTML structure and common elements.

### **Setup Instructions**
- **Continue working** with your `index.html` file from Assignment 1
- **OR create a new HTML file** called `profile.html` if you want to start fresh
- Make sure your project folder is open in VS Code

### **Requirements**
1. **Header section** with:
   - Your name
   - Navigation menu (3 placeholder links)

2. **Main content** with:
   - About section (h2 + paragraph)
   - Skills section (h2 + unordered list of 5 skills)
   - Education section (h2 + ordered list of schools/courses)

3. **Footer** with:
   - Copyright notice
   - Contact email link

4. **At least one image** with proper alt text

### **HTML Structure Template**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Add meta tags and title here -->
</head>
<body>
    <!-- Add header with your name and navigation here -->
    
    <!-- Add main section with:
         - About section (h2 + paragraph)
         - Skills section (h2 + unordered list) 
         - Education section (h2 + ordered list)
         - At least one image -->
    
    <!-- Add footer with copyright and contact email here -->
</body>
</html>
```

### **HTML Elements You'll Need**
- **Semantic elements:** `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- **Lists:** `<ul>`, `<ol>`, `<li>`
- **Links:** `<a href="url">text</a>` or `<a href="mailto:email">email</a>`
- **Image:** `<img src="filename.jpg" alt="description">`

### **Success Criteria**
- [ ] Uses semantic HTML elements correctly
- [ ] All sections are clearly structured with headings
- [ ] Image displays with meaningful alt text
- [ ] Navigation links work (jump to sections)
- [ ] No HTML validation errors

### **Bonus Challenges** (if you finish early)
- Add external links to social media profiles
- Use text formatting elements (`<strong>`, `<em>`, `<mark>`)
- Add more sections (Projects, Interests, etc.)
- Include multiple images

---

## **Assignment 3: Git Workflow Practice** ⏰ 20 minutes

### **Objective**
Practice the complete Git workflow by tracking your HTML project.

### **Setup Instructions**
- **Use your project folder** from Assignments 1 & 2 (the folder containing your HTML files)
- **Open terminal** in VS Code (Terminal → New Terminal) or use Command Prompt/Terminal app
- **Make sure you're in the correct folder** - you should see your HTML files listed

### **Step 1: Initialize and Commit** ⏰ 5 minutes

**Commands to run in terminal/command prompt:**
```bash
# Navigate to your project folder (if not already there)
cd path/to/your/project-folder

# Initialize Git repository
git init

# Add all files to staging area
git add .

# Make your first commit
git commit -m "Initial commit: Personal profile page with semantic HTML"
```

**Verification:**
- [ ] Terminal shows "Initialized empty Git repository"
- [ ] Files are committed successfully
- [ ] No error messages

### **Step 2: Create GitHub Repository** ⏰ 5 minutes

**Steps to follow:**
1. Go to [github.com](https://github.com) and sign in
2. Click green "New" button (or "+ New repository")
3. **Repository name:** `my-portfolio`
4. **Description:** "Personal portfolio website with HTML"
5. Keep it **Public**
6. **Do NOT** initialize with README
7. Click "Create repository"
8. **Copy the commands** shown on the next page

**Verification:**
- [ ] GitHub repository created
- [ ] Repository is public and empty
- [ ] Connection commands copied

### **Step 3: Connect and Push** ⏰ 5 minutes

**Commands to run (replace 'yourusername' with your actual GitHub username):**
```bash
# Connect your local repository to GitHub
git remote add origin https://github.com/yourusername/my-portfolio.git

# Set main branch
git branch -M main

# Push your code to GitHub
git push -u origin main
```

**Verification:**
- [ ] Commands run without errors
- [ ] Code appears on GitHub website
- [ ] Can view files in browser

### **Step 4: Make Changes and Update** ⏰ 5 minutes

**Instructions:**
1. **Add one more section** to your HTML (e.g., "Interests" or "Goals")
2. **Save the file**
3. **Commit the changes:**
   ```bash
   git add .
   git commit -m "Add new section to profile page"
   ```
4. **Push to GitHub:**
   ```bash
   git push
   ```
5. **View changes** on GitHub website

**Verification:**
- [ ] New section added to HTML
- [ ] Second commit made successfully  
- [ ] Changes visible on GitHub
- [ ] Commit history shows 2 commits

### **Git Commands Reference**
```bash
# Check repository status
git status

# Add files to staging area
git add filename.html        # Add specific file
git add .                    # Add all files

# Commit changes
git commit -m "Your message here"

# Push to GitHub
git push

# View commit history
git log --oneline
```

### **Troubleshooting Common Issues**

**"Not a git repository" error:**
- Make sure you're in the correct folder
- Run `git init` first

**Authentication problems:**
- Check your GitHub username and password
- Make sure repository URL is correct

**"Nothing to commit" message:**
- Make sure you saved your files
- Run `git add .` before committing

**Push rejected:**
- Make sure you're connected to the right repository
- Check repository name spelling

---

## **Assignment Completion Checklist**

### **By the end of class, you should have:**

#### **Assignment 1:**
- [ ] Basic HTML page with personal introduction
- [ ] Proper HTML5 structure
- [ ] Working in Live Server

#### **Assignment 2:**
- [ ] Complete profile page with semantic HTML
- [ ] Header, main content, and footer sections
- [ ] Lists, links, and at least one image
- [ ] Valid HTML (no errors)

#### **Assignment 3:**
- [ ] Local Git repository initialized
- [ ] GitHub repository created and connected
- [ ] Code pushed to GitHub (2+ commits)
- [ ] Can view project on GitHub website

### **Homework for Next Week:**
1. **Enhance your profile page** with more content and sections
2. **Validate your HTML** at [validator.w3.org](https://validator.w3.org/)
3. **Make 3 more commits** with meaningful changes
4. **Read CSS basics tutorial** (link will be provided)
5. **Explore GitHub** - look at other students' repositories

---

## **Need Help? Ask These Questions:**

1. **"My HTML isn't displaying correctly"**
   - Check for missing closing tags
   - Verify proper nesting of elements
   - Look for typos in element names

2. **"Git commands aren't working"**
   - Confirm you're in the right directory
   - Check if Git is properly installed
   - Verify GitHub repository URL

3. **"I can't see my changes on GitHub"**
   - Make sure you saved your files
   - Run `git add .` and `git commit`
   - Push changes with `git push`

4. **"Live Server isn't working"**
   - Check if extension is installed
   - Try right-clicking the HTML file
   - Restart VS Code if needed

**Remember:** Don't hesitate to ask your instructor or classmates for help! 🙋‍♀️🙋‍♂️ 
