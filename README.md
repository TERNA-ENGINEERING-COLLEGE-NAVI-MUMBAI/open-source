<div align="center">
  <img src="/static/github.png" width="300" height="300">
</div>

<div align="center">
  <img src="https://visitor-badge.glitch.me/badge?page_id=TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI.open-source" alt="visitors" />
  <img src="https://img.shields.io/github/issues-search/TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI/open-source?label=merged%20PRs&query=is%3Apr+is%3Aclosed+is%3Amerged&color=green" alt="Merged Pull Requests" />
</div>

<div align="center">
  Website link: <a href="https://terna-engineering-college-navi-mumbai.github.io/open-source/">https://terna-engineering-college-navi-mumbai.github.io/open-source/</a>
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

1. Clone the repository using HTTPS or SSH (If you don't have 2FA enabled).

```bash
git clone https://github.com/TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI/open-source.git
```

or PAT, more about it in the STEP 8.
```bash
git clone https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

2. Create a new branch.

```bash
git branch YourBranchName
```

3. Shift to that branch from `main` branch.

```bash
git checkout YourBranchName
```

Add `FirstName_LastName_GradYear` in your HTML branch page under the appropriate division.

4. Add all the changes you've made.

```bash
git add .
```

5. Make a commit with a message of the changes you've done. Learn more about conventional commits [here](https://www.conventionalcommits.org/en/v1.0.0/).

```bash
git commit -m 'your_message'
```

6. Shift to the master branch.

```bash
git checkout main
```

7. Merge everything from your branch to the master branch.

```bash
git merge YourBranchName
```

8. Get ready to push from your local machine.

If you don't have 2FA enabled, then use the normal HTTPS or SSH link.
```bash
git remote add <message> https://github.com/TERNA-ENGINEERING-COLLEGE-NAVI-MUMBAI/open-source.git
```

Personal Access Token (PAT) is required if you enable 2FA on your Github account [[link]](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
```bash
git remote add <message> https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

9. Push everything on your forked repository.

```bash
git push -u <message> main
```
