![Git for professionals](./git-blog-header.png)

# Remove branches locally

    git branch -d dev
    git branch -d test

# Remove branches remotely

    git push origin :dev
    git push origin :test

# Checkout another branch without commit changes

    git stash
    git checkout <branch-name>

# List all tags

    git tag

# Delete the Local Tag:

    git tag -d v1.7

# Delete the Local Tag:

    git push origin --delete v1.7
