# Lesson 1: Basic Git

Now that you have `GitHub` accounts, you will need to install `git` so that you can push code from your computer to `GitHub`. This [video](https://youtu.be/SWYqp7iY_Tc) will walk you through how to install `git` and some of the basic commands. There are dozens of git commands, most of them with options, and no developer knows them all. The most important ones are the following:

- `git init` - turns a directory (folder) into a git repository so that git can begin tracking changes in the project.
- `git clone` - this downloads a git repository from GitHub to your computer.
- `git status` - this tells you which files are being tracked, and which of the tracked files have had changes made to them. If you get confused and are not sure what to do next, it's a good idea to do this command.
- `git add` - this adds a file to the staging area so that it can be included in the next commit.
- `git commit` - once all of the files you want to take a snapshot of have been `git add`ed, this command will take the snapshot along with a descriptive message of what you changed. I like to use the `-m` option so that I can include the message at the same time: `git commit -m "Updated links in the About section."`
- `git push` - run this when you are ready to send your changes to GitHub.

## To Do

1. Clone this repository to your computer.
2. Add a file to the `turnin` directory, named <YOUR_NAME>.txt (ex. chase.txt) that simply says "Hello World!"
3. Push this new change to the GitHub repository (Note: use `git push origin master` to push. We will discuss why `git push` is not sufficient later.)

## Remember

If you find it difficult to understand what all of the commands do, or the order of them, don't worry! A lot of developers (myself included) struggle with `git` when they're first learning it. A lot of older developers refuse to learn it because it is complicated at first. Just know that in your career as a web developer, you should never shy away from learning necessary things because they are too hard. A lot of things are hard at first, but in time become second nature.
