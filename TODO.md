# Setup SSH so Git will quit asking me for my GitHub credentials
See: https://help.github.com/articles/caching-your-github-password-in-git/

I *think* I got this working by issuing:
```
$ git config --global credential.helper wincred
```
