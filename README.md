# Frontend Developer Roadmap

Welcome — this repository is a hands-on, multi-branch course designed to teach the skills needed to become a frontend developer. It’s organised as a sequence of practical lessons. Each lesson lives in its own Git branch and contains everything you need: guides, example files, exercises, and solutions.

## First Steps

1. Install WSL by typing `wsl --install` - that will install integrated ubuntu (linux) on your win PC
2. Learn Git & GitHub - `https://www.youtube.com/watch?v=mJ-qvsxPHpY` ("Git Tutorial For Dummies" by <i>
Nick White</i>)
3. Learn the basics of javascript, css & html <ul><li>html & css `https://www.youtube.com/watch?v=hu-q2zYwEYs&list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G`</li><li>js #1 `https://www.youtube.com/watch?v=iWOYAxlnaww&list=PL4cUxeGkcC9haFPT7J25Q9GRB_ZkFrQAc`</li><li>js #2 `https://www.youtube.com/watch?v=ZcQyJ-gxke0&list=PL4cUxeGkcC9jx2TTZk3IGWKSbtugYdrlu`</li><li>linux `https://www.youtube.com/watch?v=VbEx7B_PTOE&list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL&index=1`</li><ul>


## How to use this repository
1. Clone the repository:

```bash
git clone https://github.com/ozgemer/frontend-developer-roadmap
cd frontend-developer-roadmap
```

2. List available lesson branches:

```bash
git fetch --all
git branch -r
```

3. Checkout a lesson branch (example):

```bash
git checkout lesson-01-html-basics
```

4. Create a personal working branch for changes or solutions:

```bash
git checkout -b lesson-01-html-basics/yourname
# make changes locally, commit, and push
git add .
git commit -m "yourmessage"
git push
```

5. Submit a pull request against the lesson branch if you want feedback or to share improvements.

Prerequisites
- A text editor (VS Code recommended).
- Basic comfort with installing software.
- Willingness to experiment and break things — that's how you learn.

Recommended tools
- Visual Studio Code (extensions: Live Server, Auto Rename Tag, ES7+ React/Redux/React-Native snippets, Material Icon Theme, Prettier, REST Client, WSL)
- Node.js & npm recommended to install earlier on (for lessons that use build tools)
- A modern browser with DevTools (Chrome/Edge/Firefox)

Happy learning — start with `lesson-01-html-basics` and enjoy the journey.

