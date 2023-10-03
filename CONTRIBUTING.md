# Send PR directly on Github

1. Fork the repository: forking a repository creates a copy of the repository on your accoount. This allows you to freely experiment changes without affecting the main repository.

![fork](https://github.com/praistarr/Hacktoberfest2023-Ekiti-DSN/assets/53593233/9f09425a-f873-4263-a0e5-160884d63d7a)

After clicking the fork button in the image above, you'll complete the forking process by clicking the create fork button

![fork 1](https://github.com/praistarr/Hacktoberfest2023-Ekiti-DSN/assets/53593233/ef0c9fc4-b355-42a0-bc94-bb2759569389)


2. Create a branch of yours to make your contributions: creating a branch allows you to separate your changes from the main branch which can later be added to the main branch if there is no error or conflict. Else, discarded.

![branch](https://github.com/praistarr/Hacktoberfest2023-Ekiti-DSN/assets/53593233/860de698-806d-4862-9c90-b53997b3f177)


Input the name of your branch and then click "Create branch: branch-name" slightly below the branch name input area

3. When you are done creating the branch, you can start making your contributions.

![make changes](https://github.com/praistarr/Hacktoberfest2023-Ekiti-DSN/assets/53593233/71d3b8ff-159f-4c49-8870-0e640d1e5421)


5. When you're done making your contribution, compare & pull request

![compare and pull request](https://github.com/praistarr/Hacktoberfest2023-Ekiti-DSN/assets/53593233/fbd14fc7-e64d-44db-afd5-2f94423a6044)


5. Finally, send your pull request.
   You can also leave a comment to explain your contribution.

![pull request](https://github.com/praistarr/Hacktoberfest2023-Ekiti-DSN/assets/53593233/b8adc0c5-4e50-44b5-a799-1506eeed9c93)


# Send PR with git

1. Fork the repository as in the first step above

2. Clone the forked repository to your local machine

```markdown
git clone https://github.com/OSCA-Ado-Ekiti/Hacktoberfest2023-Ekiti.git
```

3. Navigate to the cloned directory

```markdown
cd Hacktoberfest2023-Ekiti
```

4. Create a branch

```markdown
git checkout -b branch_name (Creates and switches to the new branch created)
```

5. Make your contributions

6. Add, commit and push changes

```markdown
git add file_name (use . to add every files and folders in the directory)
git commit -m 'commit message'
git push origin branch_name
```

If you are having any dificulty, check this article: [https://codesandbox.io/post/how-to-make-your-first-open-source-contribution](https://codesandbox.io/post/how-to-make-your-first-open-source-contribution)
