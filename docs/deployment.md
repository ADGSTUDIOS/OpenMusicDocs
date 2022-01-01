### Pushing to GitHub Repo

## Uploading to forked repo

make sure you are in the working directory

`git add .` adds all files to be ready to push.

`git commit -m "message"` gets ready to make a change to the repo

`git push` pushs the files to your remote repo on GitHub

## Uploading to new repo

Create new repo on your GitHub account and change URL of `origin` to your repo link.

    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/username/repo.git
    git push -u origin main


## Final Deployment
- Click Settings on your repo
- Click the Pages tab
- Select a source to enable GitHub Pages. Make sure your source is the root of the `index.html` of the repo.
- Wait a few seconds on your repo
- Click Code tab
- Under Enviroment - Click `View Deployment`to view your app.

Enjoy your free Cloud Music Streaming Service Open Source Application and contribute!