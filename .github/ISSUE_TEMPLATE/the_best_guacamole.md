---
name: "\U0001F951 How to Make the Best Guacamole? " 
about: Exercise git and GitHub workflow!
title: ''
labels: 'gym'
assignees: ''

---
	
## 🥑 How to Make the Best Guacamole?
<!--Add a welcome message tagging github username -->
Welcome @ username to `intro-to-git-and-github` :tada:	 

We would like to make the best Guacamole recipy!!!

Can you please help us with your recipy
* [ ] Create your ssh keys as suggested [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
* [ ] Clone repo: `git clone git@github.com:mxochicale/intro-to-git-and-github.git`
* [ ] Share your github username to be added as contributor of this repo: 
* [ ] Create new branch: `git checkout -b #ISSUE-YOUR_NAME_AS_THE_BRANCH_NAME`
* [ ] Create a new directory using your `given-name_family-names` for your reciby in [gym/guacamole-recipies](https://github.com/mxochicale/intro-to-git-and-github/tree/main/gym/guacamole-recipes)
* [ ] Commit and push a README.md with your own recipy: 
    ```
    git add .
    git commit -m 'short message (#ISSUENUMBER)'
    git push origin ISSUENUMBER-branch-name
    ```
* [ ] Create a Pull Request and ask for review to someone else in the classroom.
* [ ] Add reviews and merge to the `main`
* [ ] Let's vote for the best Guacamole recipy!
* [ ] Feeling adventurous? Maybe generate a conflict in the recipe file and then resolve it using `git rebase`.
    ```
    git checkout main
    git pull origin main
    git checkout FEATURE_BRANCH 
    git rebase main
    #git status
    #git rebase --continue
    #git add .
    git push --force origin FEATURE_BRANCH
    ```
