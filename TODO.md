# Setup SSH so Git will quit asking me for my GitHub credentials
See: https://help.github.com/articles/caching-your-github-password-in-git/

I *think* I got this working by issuing:
```
$ git config --global credential.helper wincred
```
Nope.  I am still getting prompted for email(id) and password on every push.  Annoying.

### update 2015-06-30
OK, not sure what (if anything) that credential.helper thing did, but today I found this guy:

http://gitcredentialstore.codeplex.com/releases/view/106064

I downloaded it, ran it and then did a git push.  The push of this change will test whether
the credentials were cached or not.

### Yesss! It worked!

# Test Merging
This line added from main branch. Next task will be to merge 'branch1' into 'main'
