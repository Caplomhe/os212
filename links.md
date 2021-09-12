---
layout: "layout"
permalink: /LINKS/
---

# LINKS
1. [Introduction to Linux by The Linux Foundation](https://training.linuxfoundation.org/training/introduction-to-linux/)  
   It's an introductory course to Linux built by The Linux Foundation itself. And it's free too! Slightly more advanced from the Missing semester. It covers from Linux Basics, the Bash Shell, Network Operations, up to Local Security Principles. This will come in handy for future reference. This will come handy in the future, very interesting.

2. [Use `su -` instead of `su`](https://www.linuxquestions.org/questions/linux-newbie-8/command-usermod-not-found-385901/#post1967095)  
   Actually, depends on what are you going to do next, because `su` with the option " -" gives you the full path root would have when logging in to the system after startup. regular `su` wouldn't do such thing. So you can't, for example, add new user to the sudoer group. This little stuff of knowldge nugget is important and I haven't think about it until someone mentioned why he can't add user to sudoer group in his osp machine on OS211 Discord.

3. [GitHub's pull request is bad, according to Linus Trovalds](https://github.com/torvalds/linux/pull/17)  
   Apparently GitHub-generated Pull Requests ignores useful messages and such kind of message is important to enterprise developer such as Linus Trovalds himself. Here, Mr. Trovalds ~~rants~~ ~~roasts~~ argue about the importance of such info which makes me think twice about using github as a developer. Long commit messages can be useful to give you context about development progress, what to do, what to expect, and how did I initially use that particular solution. Such information can be useful various case such as: you are trying to get *in the moment* after long vacation or someone else is going to maintain the project. Very interesting thought, and I agree on some of his points. At the time I'm writing is post, I'm not advanced anough to understand his other points.

. [Git have aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases)  
   Git have aliases to shorten yout commands! This is interesting and useful! Not all machine have aliases so it is helpful to have one built-in into the program itself. A few aliases I found was `git undo`, it lets you undo the most recent commit just in case you can't amend it. You can register `git undo` using `git config --global alias.undo 'reset HEAD~'`. So instead of typing `git reset HEAD~` i just can type `git undo`.
