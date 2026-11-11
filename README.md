# 1. Install Git
sudo yum install git -y
# 2. Create project directory
mkdir shinywork
cd shinywork
# 3. Initialize Git
git init
# 4. Create file
vi myrepoo.txt
# Inside vi:
# Press i
# Type: Hello GitHub
# Press Esc
# Type :wq
# Press Enter
# 5. Add files
git add .
# 6. Commit
git commit -m "Initial commit"
# 7. Connect GitHub repository (replace URL)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
# 8. Push to GitHub
git push -u origin master

# Username: Your GitHub username  sanmita18
# Password: Your PAT token  

