# Demo Repository From My Pc

#### Inclusive of more markdown practice

I've just seen how to start a repo from github.com. Now, I'm looking at how to do it from my local computer.
Again, I'm going to use some **_markdown_** for practice. So far, I've learned:

1. About SSH keys and why you need them to connect to your github account
  * These also have a passphrase as an extra layer of securiy in case someone gets access to your computer.
It's not _exactly_ necessary, but it's not bad to have one :smile:.
2. A couple of git commands such as `add`, `status`, `commit`, `push`, and `ls-files`.
3. When you change a file, it gets a capital "M" on the left panel in VS Code to mean it's been modified. If you
create a new file in the folder, it gets a "U" to mean it's untracked. You'll have to use `git add .` to tell git to track them. 
4. When using `git add`, the period means to track all the files in the directory. You can optionally just type the name of the file itself.
5. Finally, when you use `git commit -m "Meaningful message here" -m "Longer description here"`, you should supply a meaningful message after the first "-m" which will populate the title bit of the commit. To add a longer description, you can optionally add another "-m" then explain what you need to explain.

It's not much, but I'm making progress. _Slow motion is better than no motion. Keep going!_

- [ ] Check this once it shows in the repo to confirm you've seen it. Just writing this to test the `git status -s` command in the terminal.
- [x] Making another change to understand the two colums that show up when you use short status i.e. the command above. The left column represents what's in the staging area, and the right represents what's in the working directory.