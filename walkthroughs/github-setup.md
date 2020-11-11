# Setup Your GitHub Repository

This walkthrough is for you to setup your mentorship family's GitHub repo.

If you do not have a GitHub account, please register at [GitHub](https://github.com/) before continuing.

## Clone the Starter Repo

NOTE: ONLY ONE MEMBER OF YOUR FAMILY NEEDS TO COMPLETE THIS TUTORIAL (but everyone should help out!) 

Open the terminal, move into your Desktop using cd, and execute this command:
```bash
git clone https://github.com/WICSMentorship2020-21/starter-website.git
```

The starter-website repo has now been cloned (or copied) onto your local computer. 

## Create Your Mentorship Family's Repo

Currently, your cloned repo is still pointing to the starter-website repo. Therefore, 
you will need to unlink your cloned copy and relink it onto a new repository. 
First, cd into the repo (or folder) you just cloned and call the command below:

```bash
git remote remove origin
```

Next, you will need to create a new repository on the GitHub website. To do so, go to [GitHub](https://github.com/) and 
click on `+` -> `new repository` in the top right corner. Here, you can create your mentorship family's repo. 
Please name the repository your family name and set the repo to public.

## Link Your Repo

You will now re-link your cloned repository to the new repo you just created. On the GitHub repo you just created, 
find and copy the URL needed to clone your repo. The URL should start with `https://`. Then call on these two commands in your terminal:

```bash
git remote add origin INSERT_URL_HERE
```

```bash
git push -u origin main
```

You may need to enter in your GitHub username and password. Please do so to complete this step.

You should now be able to see the starter code on your GitHub repo! If something doesn't look right, please ask for help before continuing. 

## Invite Your Family To Collaborate

Since your entire family will be working on this repository, you will need to invite them to add content. 

In your GitHub repo, click on `Settings` -> `Manage Access` -> `Invite a Collaborator`.
Here, invite your family members via the email they used to register their GitHub account.

## Link Your Info

In order for git to know who you are, you must add your GitHub account info through the commands below:

```bash
git config --global user.email INSERT_EMAIL_HERE
```

```bash
git config --global user.name INSERT_NAME_HERE
```

## Testing Time!

Now, let's test it out to make sure everything works. First, modify your README file to say something like 

"This repo contains team INSERT_TEAM_NAME's mentorship family memories."

Next, you'll need to push your changes to your repo:
1. Create a new branch with this command (you can name your branch anything e.g. UpdateReadme):

```bash
git checkout -b YOUR_BRANCH_NAME
```

2. Use git add to add your changes:
```bash
git add README.md
```

3. Commit your changes:
```bash
git commit -m "Update the README.md file."
```

4. Finally, push your changes onto your repo:
```bash
git push origin YOUR_BRANCH_NAME
```
Your changes should have been pushed onto your GitHub repo. You can now create a pull request (PR) and merge your changes. 

Use this tutorial on [Creating Pull Requests](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request). Once you've created the PR, you can simple `merge changes` on the bottom.

Please make sure everything is working up to this point before continuing!

## Your GitHub Repo is Ready To GO!

Congrats! You have successfully set up your repository :)

Feel free to move on to the second walkthrough!
