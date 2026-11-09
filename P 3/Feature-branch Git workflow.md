# P3 – Feature Branch Workflow

# 1. Open your project folder
cd my-portfolio

# 2. Check current Git status
git status

# 3. View existing branches
git branch

# 4. Create a new feature branch
git branch feature/about-section

# 5. Switch to the feature branch
git checkout feature/about-section

# 6. Create a new HTML file
touch about.html

# 7. Add changes to the staging area
git add .

# 8. Commit the changes
git commit -m "Add about section"

# 9. Switch back to main branch
git checkout main

# 10. Merge feature branch into main
git merge feature/about-section

# 11. Push changes to GitHub
git push origin main

# 12. Delete the feature branch
git branch -d feature/about-section

# 13. Check final branch status
git branch
git status