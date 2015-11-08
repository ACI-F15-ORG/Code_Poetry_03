## Code && Poetry

### Due Date : November 17

### Goals:

1. Read
2. Create a Code Poem
3. Turning In

#### 1. Read
On the Google drive 
_Creative Code_, it contains several 1-2 page writings by John Maeda, John Simon Jr., and Scott Snibbe. 

_Cosmicomics_, by Italo Calvino, ask someone to pick a chapter, read that chapter. If instructions unclear, read Chapter 1 or lucid dream about the moon. Oulipo.  

_Steel Mind of the Software Artist_, if you have time, read this one. 

#### 2. Create a Code Poem
Create a Code Poem in any progamming language: C, Python, LISP, Go, Pure Data, VRML, Java, etc. There are three requirements:

1. It must be "code"
2. It must be a "poem"
3. It must run, which implies that it may need to compile, further implying instructions may be necessary

#### 3. Turning In
First is to make your own repository of your project and sync it to github. 

Then, Clone this assignment directory to your computer. From within the folder of the clone, use the terminal. 

Make a branch, replace _your-branch-name_ with something unique, rcsid, etc.

```bash
git branch your-branch-name
```
Checkout _your-branch-name_ so that we're working in that branch.

```bash
git checkout your-branch-name
```

Replace _remote-url_ with something like _https://github.com/shawnlawson/shawnmodule.git_ and _linked-folder-name_ with your name _shawnlawson_

```bash
git submodule add remote-url linked-folder-name
```

Then you'll need to add and commit.

```bash
git commit -a -m 'adding submodule'
```

You'll need to push your branch to the remote.

```bash
git push origin your-branch-name
```
You may run up against a GIT 2.0 error. 
http://stackoverflow.com/questions/13148066/warning-push-default-is-unset-its-implicit-value-is-changing-in-git-2-0

Do the simple solution

```bash
git config --global push.default simple
```
From the github web interface for this assignment's repository you'll create a new pull request.

Base will be master, compare will be _your-branch-name_

Create the request. You shouldn't accept your own pull request. Someone else, me or another person, should review the request to make sure none of the other files in the repository were modified before accepting. Sort of like a checks and balances system. 

__Warning__ you can only push if you're a member of our organization. And, do not delete anything from the repository before pushing.

