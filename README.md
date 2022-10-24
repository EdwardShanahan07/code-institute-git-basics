# Git Basics Commands
`git init` Initialise a new git repository 

`git status` show the status of the git repository 

`git add` will add files to the staging area

```bash
git add hello.txt
```

git commit will commit to git repository 

```bash
git commit -m "Add hello.txt file"
```

## About Commit Messages

In the previous unit, we discussed how to add commit messages. Here are some answers to commonly asked questions:
What should my commit message say?
Ideally, your message should explain what the commit contains. The commit message should be 50 characters or less but should be detailed.
Here are some examples of bad commit messages:
`Fixed error`
`Added page`
`Updated README.md`
Why are these bad? They do not give any meaningful information about what the commit contains. Also, it's recommended that commit messages are written using the imperative mood as a command or request. Imagine that you are prefacing every commit message with the words, "This commit will..." Here are the improved versions:
`Fix the bug causing the main image to overflow screen`
`Add boilerplate to about.html for the About Me page`
`Add testing & deployment information to README.md`
Notice that these messages actually explain something about what the commit contains, and they are written in the imperative mood. That's the kind of detail we should aim for.
Why does it matter for a personal project?
The main reason it matters is so that you (and anyone else who is interested in your project) can see the history and roll things back if required. We want you to learn good software development habits throughout the programme. Writing clear, meaningful commit messages is an important part of being a good citizen in the development community.
Additionally, you will be assessed on the quality of your commit messages when you submit your end-of-module projects, so it makes sense to take some time to write descriptive commit messages.
Is there a recommended format for commit messages?
If your message says something like: `Make heroImage.jpg in index.html responsive`, then that's a good message. You could adopt the convention that some developers use of prefixing their commit messages with `feat` for feature, `fix` for a bugfix, `style` for changes to your CSS, `docs` for changes related to documentation, `refactor` for refactored code or `maint` for general maintenance.
So, the above example would look like this: `fix: Make heroImage.jpg in index.html responsive`. If you were updating your README file, you could have a commit message like this: `docs: Add testing & deployment sections to README`.
If you do choose to use a format like this, then be consistent throughout your project and use it for every commit.
How often should I commit?
That is entirely up to you. A good rule of thumb is to commit after every major change or addition of a new page or feature. Smaller changes, such as grammar, spelling and minor content changes, don't necessarily need their own commit each time, but group about four or five of them into one commit.
Can I change a commit message?
Your git commit messages are your project's history. Therefore, we would strongly recommend getting into the habit of writing considered commit messages. Although technically, a commit message can be amended, by doing so you are rewriting history. Even if you are the only contributor, this amendment leads to problems, as the GitHub history will no longer match the local git history. It has much worse consequences in a collaborative project as then your collaborators will have a different history, and they will have to make manual changes. In either instance, you will have brought your project to a grinding halt and will have painful remedial work to do.
Keep in mind these things as you progress through the programme, and make sure you are always writing descriptive and meaningful commit messages. We suggest that you refer back to this section when you start your milestone project.

git rm —cached file.name will remove changes from stage area 

```bash
git rm --cached hello.txt
```

`git log` will show previous git commits

`git diff` will show the difference between two files

```bash
git diff hello.txt
```

git reset will revert to a previous commit 

```bash
git reset --hard ff11f9
```

.gitignore file is used to files or folders you dont want added to git

```bash
bye.txt
```