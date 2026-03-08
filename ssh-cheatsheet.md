==============================
GitHub SSH Git Commands (Pi)
==============================

# Clone repo
git clone git@github.com:<username>/<repo>.git
# Example: git clone git@github.com:rafael5/zshell.git

# Set or update SSH remote
git remote set-url origin git@github.com:<username>/<repo>.git
git remote -v  # verify
# Example: git remote set-url origin git@github.com:rafael5/zshell.git

# Check SSH connection
ssh -T git@github.com

# Stage & commit
git add .
git commit -m "Your message"

# Push & pull
git push origin <branch>  # Example: git push origin main
git pull origin <branch>  # Example: git pull origin main

# Add new remote
git remote add origin git@github.com:<username>/<repo>.git

# Branching
git checkout -b <new-branch>  # create & switch
