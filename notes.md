# directory structure
Main page is [./index.md]
Subpages are in folder [./pages]
Images go in [./pages/images]

# to push to github
git add .
git commit -m "message"
git push -u origin main

# github account config / ssh keys / pushing
Github has been configured & setup with ssh keys to push to improbabilityfield system-wide for totalperspectivortex-windows (done via Git Bash) and protosophon-ubuntu (done via terminal). To set up pushing to a different account, see:

- https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup:
The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
Again, you need to do this only once if you pass the --global option, because then Git will always use that information for anything you do on that system.
==If you want to override this with a different name or email address for specific projects, you can run the command without the --global option when you’re in that project.==

- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account