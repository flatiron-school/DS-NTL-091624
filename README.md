# DS-NTL-091624's Cohort Repository!

A repository for all lectures, slides, and other resources for the Flatiron School's Live Data Science 091624 Cohort.

![cool data graphic from gihpy](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExMGJpdDM5Y2JyMDhzaDMyaGgzN3VlNmZlZmR4bjh1ODdnaXlxYmV0NSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l46Cy1rHbQ92uuLXa/giphy.gif)

## Instructions to Connect to this Repository:

**We will be going through these instuctions several times during the first week or so of class - no rush!**

1. FORK this repository, creating a copy on your own GitHub account

2. Then clone your fork down to your local computer
```
git clone https://github.com/[yourusername]/DS-NTL-091624.git
```

3. Add the original non-forked `/flatiron-school/` version as the remote `upstream` within your local forked clone, this will allow you fetch/pull future material
```
git remote add upstream https://github.com/flatiron-school/DS-NTL-091624.git
```

4. You can make changes to any of your local notebooks now and it should not conflict with any new or updated material posted! Remember to push your changes to your forked version of the repo and not the upstream if you want to put your local changes up online and save any notes:
```
git add [filename]
git commit -m 'message here'
git push origin main
```
#### I would encourage everyone to push daily if you are taking lecture notes within the code notebooks!

## Instructions to Fetch new Material:

1. Grab the changes from the upstream remote repo
```
git fetch upstream
```

2. Merge new changes onto your local repo
```
git merge upstream/main -m "meaningful message about what you're updating"
```