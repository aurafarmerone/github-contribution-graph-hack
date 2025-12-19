# 🟩 GitHub Contribution Commit Graph Hack

Create **custom patterns, text, or designs** on your GitHub contribution graph using automated commits.

This project is a **Python-based script** that takes a generated `pattern.json` file and converts it into **real GitHub commits**, making your contribution graph display the desired pattern using green dots.

> 🎯 Built for learning, fun, and open-source experimentation.


## ✨ What Does This Project Do?

#### 🕰️Act as a Time Machine for Your GitHub Graph

Think of this project as a **time machine** 🚀 for your GitHub contribution graph.

We all have moments where:
- We were inactive for months
- Made mistakes
- Forgot to push code
- Or simply didn’t know GitHub well enough

This tool lets you **travel back in time** and visualize patterns on your contribution graph by converting a generated `pattern.json` into **real commits with past dates**.

It doesn’t change who you are —  
it just helps you **experiment, learn, and have fun** with how GitHub graphs work.

> ✨ Wash away old gaps, explore commit history mechanics, and create something visually cool — responsibly.


## 🖼 Example Output
Here’s what a generated pattern looks like on a GitHub profile:

![Contribution Graph Example](assets/patternBeforeAfter.png)



## 🧠 How It Works (Simple Explanation)

GitHub contribution graph is:
- **7 rows** → days of the week  
- **52 columns** → weeks in a year  

This script:
1. Reads your pattern grid  
2. Converts active cells into commit dates  
3. Creates commits using Git  
4. GitHub shows them as green dots  

No fake rendering — **real commits, real graph**.


## 🚀 How To Use

### 1️⃣ Clone This Repository

```bash
git clone https://github.com/aurafarmerone/github-contribution-graph-hack.git
cd github-contribution-graph-hack
```


### 2️⃣ Generate `pattern.json`

This script **requires a pattern file**.

You can generate it using my pattern generator website or from my repository:

 🌐 **GitHub Pattern Generator**  
👉 https://github-pattern-generator.web.app/

**OR**

 🌐 **GitHub  REPOSITORY**  
👉 https://github.com/aurafarmerone/github-pattern-generator

Steps:
- Open the website  
- Design your text or pattern  
- Download `pattern.json`  
- Place it in this repository by replacing old "pattern.json" 

#### 🖼 Website Generated Pattern Example
Here’s what a generated pattern looks like and remember to download:

![Website Pattern Example](assets/web-example.png)


### 3️⃣ Configure Git Identity (IMPORTANT)

Your commit email must match your GitHub account:

```bash
git config user.name "Your Name"
git config user.email "your-email@users.noreply.github.com"
```

### 4️⃣ Run the Script

```bash
python script.py
```
Now, Script will ask for inwhich year want to draw your pattern 
> Enter year to draw pattern: 2024

This will:
- Create multiple commits  
- Assign historical dates  
- Encode your pattern into the contribution graph  


### 5️⃣ Push Commits to GitHub

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/github-contribution-graph-hack.git
git push -u origin main
```

⏳ Wait **5–15 minutes**, then check your GitHub profile.



## 📺 **Full YouTube Walkthrough** 
### 🎥 Video Tutorial

[![GitHub Contribution Graph Hack Tutorial](assets/thumbnail.png)](https://www.youtube.com/watch?v=ekk1_MQ9JfQ)

👉 Video Link: https://www.youtube.com/watch?v=ekk1_MQ9JfQ



## ⚠️ Disclaimer

This project is created **just for fun, learning, and experimentation**.

❗ Please do **NOT**:
- Mislead others using your contribution graph  
- Claim fake activity during interviews  
- Use this for unfair advantages  

Be honest — skills matter more than graphs.


## 🤝 Contributing

Want to improve this project?

Please read **CONTRIBUTING.md** for guidelines on:
- Reporting issues  
- Suggesting features  
- Submitting pull requests  

All contributions are welcome ❤️
 

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.



## ❤️ Credits

Made with ❤️ by **Aura Farmer**  
If you find this project useful, consider giving it a ⭐ on GitHub!


