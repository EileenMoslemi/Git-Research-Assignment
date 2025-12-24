# What Happens Under the Hood When You Fork or Clone?

## When You Fork
- GitHub creates a server-side copy of the repository
- The fork remains linked to the original repo
- No files are downloaded to your computer

## When You Clone
- Git downloads the full repository history
- A `.git` folder is created locally
- A remote called `origin` is set automatically

Forking happens on GitHub servers, while cloning happens on your local machine.

## Source
https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes
