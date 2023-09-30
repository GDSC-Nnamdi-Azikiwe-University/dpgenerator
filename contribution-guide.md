# Contribution Guidelines 🙌

This documentation contains a set of guidelines to help you during the contribution process to this project. We happy to welcome all the contributions from anyone willing to add to this repository. Thank you for helping out and remember, No contribution is too small.

## Steps To Follow Before You Contribute 🛠️

Please make sure you follow this guidelines so your code can be merged as quickly as possible

1. On the [GitHub page for this repository,]('https://github.com/GDSC-Nnamdi-Azikiwe-University/dpgenerator') click on the Button "Fork".

![Fork repo](public/readme-assets/fork-gdsc.png)

1. Clone your forked project to your local computer

![Clone repo](public/readme-assets/clone-gdsc.png)

- for example, run this command inside your terminal:

```bash
git clone https://github.com/<your-github-username>/dpgenerator.git
```

1. Shift into project folder

```bash
cd path to project folder
```

4. Before you make any changes, keep your fork in sync to avoid merge conflicts:

```bash
git remote add upstream https://github.com/GDSC-Nnamdi-Azikiwe-University/dpgenerator.git
git pull upstream main
```

5. After adding the upstream and checking that all files are up to date, create new branch before fixing or editing any files.

```bash
  git checkout -b <branch-name>
```

6. Done fixing any issue ? Add the changes with git add, git commit (write a good commit message, if possible):

```bash
git add file or files
git commit -m "descriptive message"
```

7. Push your changes to your repository and make a pull request:

```bash
git push origin <branch-name>
```

1. Create a pull request on the [GitHub page for this repository,](' https://github.com/GDSC-Nnamdi-Azikiwe-University/dpgenerator.git')

![Clone repo](public/readme-assets/compare-code.png)
