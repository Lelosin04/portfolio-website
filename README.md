
# portfolio-website
## How I Update My Portfolio Website

### Previously...

Before connecting GitHub, I updated my portfolio manually:

1. Made changes to my website files in VS Code.
2. Saved the updated `index.html`
3. Used the AWS S3 CLI and uploaded the new index.html file
4. Went to AWS Amplify and clicked deploy changes. Waited for AWS Amplify to redeploy the site.
  

### Currently...

Now my portfolio uses Git and GitHub with AWS Amplify:

1. Make changes to my website files in VS Code.
2. Save the files.
3. Check the changes:
Pull the latest version of the website 
```bash
git pull origin main .
```

Stage the changes
```bash
git add .
```
Commit the changes
```bash
git commit -m "Describe the update or what you changed"
```
Push the changes to GitHub
```bash
git push
```
To check the now updated version 
```bash
git status
```
P.s.: to undo a commit run
```bash
git reset --soft HEAD~1
```
