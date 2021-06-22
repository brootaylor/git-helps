# GIT Helps

GIT helps for when I've forgotten various commands

## Change from `master` to `main`

```bash
# This is for the local instance of the repo
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```

### Other important steps:

- Remember to change the name of the branch on the remote instance
- Change the name of the `production` branch to `main` on something like Netlify (if that's what you're using)

***
