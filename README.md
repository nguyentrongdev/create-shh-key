# craete-ssh-key
1. To generate a new SSH key pair, use the following command: ssh-keygen -t rsa -C "your.email@example.com" -b 4096
2. git config --global user.name "Admin"
3. git config --global user.email "admin@vinasupport.com"


# gitlab to github repo

git clone <old_url>
cd <repo_dir_name>

// new_remote
- git remote add new_remote <new_url>
- git push --all new_remote
// replace remote
git remote -v
git remote set-url origin git@github.com:nguyentrongdev254/web-truyen-tranh.git


git clone https://oauth2:token@gitlab.com/account_name/repo_name.git

# Format
git clone https://<USERNAME>:<TOKEN>@github.com/<USERNAME>/<REPO>.git

# Example
git clone https://johndoe:ghp_xxxxxxxxxxxx@github.com/johndoe/private-repo.git
# Example Remote
git remote add origin git@github-personal:nguyentrongdev/thieponline.git
