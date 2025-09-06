# 🚀 Git Workshop - Team Collaboration Exercise

## 📋 Overview
This repository is a template for the BU Git Workshop focusing on collaborative web development using Git version control. Teams of 4-5 members will practice essential Git workflows including branching, committing, and merging.

## 🎯 Workshop Objectives
- Learn Git branching and merging workflows
- Practice collaborative development
- Understand proper commit message conventions
- Experience conflict resolution (if any arise)

## 📝 Tasks Checklist

### Task 1: Update Team Information
- [ ] Clone this repository to your local machine
- [ ] Open `index.html` in your text editor
- [ ] Replace the placeholder information `[Full Name X]`, `[Nickname X]`, and `[Student ID X]` with actual team member details
- [ ] Save the file

### Task 2: Create Personal Branches
Each team member must:
- [ ] Create a new branch named after yourself
- [ ] Switch to your personal branch

```bash
# Create and switch to your branch
git checkout -b your-name

# Or alternatively
git branch your-name
git checkout your-name
```

### Task 3: Make Individual Commits
- [ ] Make changes to `index.html` (add your personal information)
- [ ] Stage your changes
- [ ] Create a commit with a meaningful personal message

```bash
# Stage your changes
git add index.html

# Commit with your personal message
git commit -m "Add [Your Name] information to team members"
```

### Task 4: Merge to Main Branch
- [ ] Switch back to the main branch
- [ ] Merge your personal branch into main
- [ ] Push changes to the remote repository

```bash
# Switch to main branch
git checkout main

# Merge your branch
git merge your-name

# Push to remote
git push origin main

# Optional: Delete your branch after merging
git branch -d your-name
```

## 🛠 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [REPOSITORY_URL]
   cd bu-git-workshop
   ```

2. **Open index.html in a browser to see the current template**

3. **Follow the tasks above in order**

## 📁 Repository Structure
```
bu-git-workshop/
├── README.md           # Workshop instructions
├── index.html          # Main HTML file to edit
└── .gitignore         # Git ignore rules
```

## 👥 Team Member Template
Replace the placeholders in `index.html` with:
- **Full Name:** Complete first and last name
- **Nickname:** Preferred name or nickname (in quotes)
- **Student ID:** University student identification number

## 🎨 Features
The HTML template includes:
- Responsive design that works on all devices
- Modern CSS styling with gradients and animations
- Card-based layout for team members
- Built-in Git command reference
- Visual instructions for the workshop

## 🔧 Troubleshooting

### Common Git Issues:
- **Merge conflicts:** If two people edit the same line, resolve conflicts manually
- **Branch not found:** Make sure you're spelling your branch name correctly
- **Permission denied:** Ensure you have write access to the repository

### Commands to Check Status:
```bash
git status          # Check current branch and file status
git branch          # List all branches
git log --oneline   # View commit history
```

## 🎓 Learning Outcomes
After completing this workshop, you will:
- Understand Git branching strategies
- Know how to create meaningful commit messages
- Experience collaborative development workflow
- Practice merging branches safely
- Learn basic conflict resolution

## 📞 Support
If you encounter issues during the workshop:
1. Check the troubleshooting section above
2. Ask your instructor or TA for help
3. Use `git status` to understand your current state

## 🏆 Completion
Your workshop is complete when:
- [ ] All team members' information is added to `index.html`
- [ ] Each member has created their own branch
- [ ] Each member has made at least one commit
- [ ] All branches have been merged to main
- [ ] The final result displays all team members correctly

---
**Happy coding! 🎉**