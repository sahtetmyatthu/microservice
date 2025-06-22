# microservice
 Master Microservices with SpringBoot,Docker,Kubernetes
 ✅ Recommended: Use SSH authentication
 This is secure, convenient, and avoids password prompts entirely.

Step-by-step:
Generate SSH key (if you don’t have one):


ssh-keygen -t ed25519 -C "your_email@example.com"


Copy the SSH public key to clipboard:


cat ~/.ssh/id_ed25519.pub | pbcopy
Add the key to GitHub:

Go to GitHub → Settings → SSH and GPG keys → New SSH key

Paste the key and save

Change your Git remote to use SSH:

bash
Copy
Edit
git remote set-url origin git@github.com:sahtetmyatthu/microservice.git
Try pushing again:

bash
Copy
Edit
git push -u origin main