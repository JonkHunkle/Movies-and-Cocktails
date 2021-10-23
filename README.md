## Creating a branch

### Before you create your branch

git checkout main<br/>
git pull

### Create your branch

git checkout -b &lt;initials&gt;/&lt;branch name&gt;

### Add your changes to your branch

git add .
git commit -m "message about your changes"<br/>

### Make sure you have no conflicts with main

git checkout main<br/>
git pull<br/>
git checkout &lt;initials&gt;/&lt;branch name&gt;<br/>
git merge main

### Commit and push changes to github

git push

(if you had to resolve conflicts with main - do another git commit)

### Go to github repo to create pull request to merge your changes into our main branch

## Github Deployed Application

[https://jonkhunkle.github.io/Project-1/](https://jonkhunkle.github.io/Project-1/)
