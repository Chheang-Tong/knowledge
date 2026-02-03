- Initialize git (if not already)

```text
git init
```

- Check status (optional but good habit)

```text
git status
```

- Add File to Git Hub

```text
git add .
```

- Add specific file

```text
git add README.md
```

- Commit Project

`text git commit -m "Initial commit"`
Connect local project to GitHub

- git remote add origin https://github.com/username/repo-name.git
  Check remote
- git remote -v

* =================================================================
* Push to GitHub
* ==============
* If branch is main:

```text
git branch -M main
git push -u origin main
```

If branch is master:

- # git push -u origin master

```text
git add .
git commit -m "your message"
git push
```

Remote already exists

- git remote remove origin
- git remote add origin https://github.com/username/repo-name.git
