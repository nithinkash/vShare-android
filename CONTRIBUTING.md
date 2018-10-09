# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. 

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Pull Request Process

### 1. Explore

If there is some issue or bug, you are interested in and no one else is working 
on the issue, you may take it up ( just leave a comment on the issue).

### 2. Fork & create a branch

If this is something you think you can fix, then create a branch with a 
descriptive name.

```sh
git checkout -b branch-name
```

### 3. Build & run the project locally
```sh
git clone https://github.com/user/vShare-android.git
cd vShare-electron
npm install
npm start
```

### 4. Implement your fix or feature

At this point, you're ready to make your changes! Feel free to ask for help;
everyone is a beginner at first :smile_cat:

Update the README.md with details of changes to the interface, this includes new environment 
   variables, exposed ports, useful file locations and container parameters.

### 5. Make a Pull Request

At this point, you should switch back to your master branch and make sure it's
up to date with Active Admin's master branch:

```sh
git remote add upstream https://github.com/vShareApp/vShare-android.git
git checkout master
git pull upstream master
```

Then update your feature branch from your local copy of master, and push it!

```sh
git checkout branch-name
git rebase master
git push --set-upstream origin branch-name
```

Finally, go to GitHub and [make a Pull Request][] :D

