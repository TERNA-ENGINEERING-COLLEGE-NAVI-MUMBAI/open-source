<div align="center">
  <img src="/static/github.png" width="300" height="300">
</div>

<div align="center">
  <img src="https://visitor-badge.glitch.me/badge?page_id=TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI.open-source" alt="visitors" />
  <img src="https://img.shields.io/github/issues-search/TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI/open-source?label=merged%20PRs&query=is%3Apr+is%3Aclosed+is%3Amerged&color=green" alt="Merged Pull Requests" />
</div>

<div align="center">
  🌐 Website link: <a href="https://terna-engineering-college-navi-mumbai.github.io/open-source/">https://terna-engineering-college-navi-mumbai.github.io/open-source/</a><br>
<!--🖥 Presentation link: https://drive.google.com/file/d/1PB0TN9xqt0HvJ9f5IcmEVnP2A4WjNoCJ/view?usp=sharing-->
</div>

## Git installation

Install Git from this link:- <a href="https://git-scm.com/downloads" target="_blank">https://git-scm.com/downloads</a>

To check the Git version

```bash
git --version
```

To set the global Git username & email address

```bash
git config --global user.name "your name"
git config --global user.email "your email"
```

## STEPS to contribute

Before you follow all these STEPS, make sure you `fork` the repository in your account.

### 1. Clone the repository.

This will basically download the git initialized repository on your computer.

If you don't have 2FA enabled, then use the normal HTTPS or SSH link.
```bash
git clone https://github.com/TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI/open-source.git
```

Personal Access Token (PAT) is required if you enable 2FA on your Github account [[link]](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
For that, use the following command instead of the normal URL command.
```bash
git clone https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

### 2. Create a new branch.

Creating a new branch allows you to isolate your changes from the master (main) branch. If your changes goes well, you always have the option to merge your changes into the master branch. If things don't go so well you can always discard the branch or keep it within your local repository.

```bash
git branch YourBranchName
```

### 3. Shift to that branch from master (`main`) branch.

By default you're on main branch. So to switch from main, use the following command.

```bash
git checkout YourBranchName
```

Add your `GitHub profile link` and your `FirstName_LastName_GradYear` in the HTML branch page under the appropriate division.

### 4. Add all the changes you've made.

```bash
git add .
```

### 5. Make a commit message of the changes you've made. Learn more about conventional commits [here](https://www.conventionalcommits.org/en/v1.0.0/).

```bash
git commit -m 'Add my contribution'
```

### 6. Shift to the master (`main`) branch.

Now, switch back to main branch to merge all the changes.

```bash
git checkout main
```

### 7. Merge everything from your branch to the master (`main`) branch.

```bash
git merge YourBranchName
```

### 8. Get ready to push from your local machine.

You cannot directly push the changes from your local machine, to do that we have to create a new connection record to a remote repository. After adding a remote, you'll be able to use as a convenient shortcut for in other Git commands.

If you don't have 2FA enabled, then use the normal HTTPS or SSH link.
```bash
git remote add <message> https://github.com/TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI/open-source.git
```

Personal Access Token (PAT) is required if you enable 2FA on your Github account [[link]](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
For that, use the following command instead of the normal URL command.
```bash
git remote add <message> https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

### 9. Push everything on your forked repository.

This will push all the changes you've made to the master (`main`) branch of your forked repository.

```bash
git push -u <message> main
```

Now, click on `Pull Request` button, you'll have the option to **create a pull request**. i.e., `<your forked repo> -> <original repo>`, That's it you're done! 
