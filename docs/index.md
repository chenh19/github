---
title: "How to Use GitHub: A 5-Minute Tutorial"
toc: true
---

### 1. Sign up to GitHub

- If you haven’t already, you may sign up to GitHub [here](https://github.com/signup).

<div style="text-align:center;"><img src="./images/1-1.png" width="85%"></div>

<details>
<summary>**Note:**</summary>
<div style="font-size: 0.9em">

– If you’ve never used **Markdown** before, it’s a plain text format with simple symbols that allow other software to interpret the structure—like headings, lists, or links. It’s very easy to learn and especially helpful when working with GitHub. Check out the [basic syntax](https://www.markdownguide.org/cheat-sheet/#basic-syntax), which covers the most common use cases.

</div>
</details>


### 2. Create a new repository

- Now, create a new repository.

<div style="text-align:center;"><img src="./images/2-1.png" width="85%"></div>

- Provide the necessary information to set up your repository.

<div style="text-align:center;"><img src="./images/2-2.png" width="85%"></div>

- Done.

<div style="text-align:center;"><img src="./images/2-3.png" width="85%"></div>

<details>
<summary>**Note:**</summary>
<div style="font-size: 0.9em">

- There’s nothing fancy about a **repository**—you may simply think of it as a **folder**.
- I usually go with [GPL 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html#SEC1). You may read about [open-source licenses](https://www.wikiwand.com/en/articles/Open-source_license) and choose one that suits your needs. GitHub also provides [a list of licenses](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#searching-github-by-license-type) you can choose from when creating a repository.

</div>
</details>


### 3. Edit the README file

- Click the pencil button to edit.

<div style="text-align:center;"><img src="./images/3-1.png" width="85%"></div>

- Make your edits and then commit.

<div style="text-align:center;"><img src="./images/3-2.png" width="85%"></div>
<div style="text-align:center;"><img src="./images/3-3.png" width="85%"></div>

- Done.

<div style="text-align:center;"><img src="./images/3-4.png" width="85%"></div>


### 4. Create a new file

- Create a new file in the repository.

<div style="text-align:center;"><img src="./images/4-1.png" width="85%"></div>

- Make your edits and then commit.

<div style="text-align:center;"><img src="./images/4-2.png" width="85%"></div>
<div style="text-align:center;"><img src="./images/4-3.png" width="85%"></div>

- Done.

<div style="text-align:center;"><img src="./images/4-4.png" width="85%"></div>


### 5. Upload files

- Upload files to the repository.

<div style="text-align:center;"><img src="./images/5-1.png" width="85%"></div>

- Drag and drop your files, then commit.

<div style="text-align:center;"><img src="./images/5-2.png" width="85%"></div>

- Done.

<div style="text-align:center;"><img src="./images/5-3.png" width="85%"></div>


### 6. Add link to your website

- In some cases, you might have a separate website for your repository. Click the gear icon to add the link.

<div style="text-align:center;"><img src="./images/6-1.png" width="85%"></div>
<div style="text-align:center;"><img src="./images/6-2.png" width="85%"></div>
<div style="text-align:center;"><img src="./images/6-3.png" width="85%"></div>

<details>
<summary>**Note:**</summary>
<div style="font-size: 0.9em">

- If you’re interested in how to create a website using GitHub, you may check out [this tutorial](https://chenh19.github.io/Quarto/misc.html).

</div>
</details>


### 7. Create a release

- At some point, you might want to archive and release a specific version of your repository. Click the “Create a new release” button.

<div style="text-align:center;"><img src="./images/7-1.png" width="85%"></div>

- Create a new tag.

<div style="text-align:center;"><img src="./images/7-2.png" width="85%"></div>

- Enter the title and description, upload relevant files (if any), and publish.

<div style="text-align:center;"><img src="./images/7-3.png" width="85%"></div>

- Done.

<div style="text-align:center;"><img src="./images/7-4.png" width="85%"></div>
<div style="text-align:center;"><img src="./images/7-5.png" width="85%"></div>


### 8. Using command line

- If you're a more advanced user, you might prefer using the command line to pull the repository to your local machine, make changes, and then push them back to GitHub.
- You'll need to set up SSH access for your GitHub account. You may check out [this tool and tutorial](https://github.com/chenh19/git_ssh).
- Assuming you’ve already created a repository (see [Step 2](https://chenh19.github.io/github_tutorial/#create-a-new-repository)), find the SSH URL for your repository.

<div style="text-align:center;"><img src="./images/8-1.png" width="85%"></div>

- Create a folder on your local machine (replace ```test``` with your desired folder name):

<p style="text-indent: 2em;">```mkdir -p ./test/ && cd ./test/"```</p>

- Initialize the folder (replace ```git@github.com:chenh19/test.git``` with your SSH URL):

<p style="text-indent: 2em;">```git init && git remote add origin git@github.com:chenh19/test.git```</p>

- Pull your repository (replace ```git@github.com:chenh19/test.git``` with your SSH URL):

<p style="text-indent: 2em;">```git pull git@github.com:chenh19/test.git```</p>

- Make your edits locally.

- Push to your GitHub:

<p style="text-indent: 2em;">```git add --all && git commit -a -m "update" && git push -u origin main```</p>

<details>
<summary>**Note:**</summary>
<div style="font-size: 0.9em">

- This tutorial is intended for beginners and doesn't cover concepts like "branches," "pull requests," and etc. For more advanced or collaborative development, you may want to learn about workflows for merging branches.

</div>
</details>


### 9. Repository settings

- You might want to change the repository’s visibility, transfer ownership, or delete it. You can find these options under the "Settings" tab.

<div style="text-align:center;"><img src="./images/9-1.png" width="85%"></div>
<div style="text-align:center;"><img src="./images/9-2.png" width="85%"></div>


### 10. End

- Now you've learned the basics of how to use GitHub. Good luck and happy developing!
