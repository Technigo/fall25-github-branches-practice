# 🧑‍💻 Git Collaboration Challenge – Fork + Pull Request

In this activity, you’ll practise how developers collaborate on GitHub **without being added as collaborators** — just like in open source projects!

You’ll learn how to:
- **Create a new branch**
- **Commit and push changes**
- **Open a Pull Request** to the original repo

---

## 🌟 Your task
We’re building a simple **“Team Page”** together!  
Everyone will add **their own name** to a shared list in the `index.html` file.

---

## 🧭 Step-by-step instructions

### 1. Breath

---

### 2. Clone your fork
Now, clone *your version* of the repo to your computer:

```
git clone https://github.com/YOUR-USERNAME/fall25-github-branches-practice.git
```
Then move into the project folder:

```
cd fall25-github-branches-practice
```

---

### 3. Create a new branch
Create a new branch for your changes — never work directly on main!

```
git checkout -b add-your-name
```

---

### 4. Make your change
Open the index.html file in your code editor and add your name inside the list.

Example:
```
<ul>
  <li>Matilda Brunemalm</li>
  <li>Jennie Dalgren</li>
  <li>Your Name Here ✨</li>
</ul>
```

---

### 5. Add, commit and push your changes

```
git add .
git commit -m "Added my name to the list"
git push origin add-your-name
```

---

### 6. Open a Pull Request (PR)
Go to your fork on GitHub.

You’ll see a banner suggesting: “Compare & pull request” – click it.

Make sure the base repo is the original one (not your fork).

Add a title and short description for your PR.

Click Create pull request 🎉

💡 You just asked to merge your changes into the main project — this is exactly how open source collaboration works!

---

### 7. Wait for review and merge
Your teacher will review and merge your PR into the main repo.
Once merged, your name becomes part of the project!


---

## 💬 What you’ve learned
✅ The difference between collaborating in a shared repo vs contributing through a fork

✅ How to create and work on branches safely

✅ How to open a Pull Request and contribute to someone else’s project
