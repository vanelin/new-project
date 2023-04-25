## Step-by-step instructions on how to create a new GitHub repository for "new-project" and add a development branch:

1. Log in to your GitHub account.
2. Click on the "+" sign in the top right corner of the screen and select "New repository".
3. Type "new-project" as the name for the repository and add a brief description if desired.
4. Select "Public" or "Private" depending on your preference.
5. Click on the "Create repository" button.

Now that you have created the repository, you need to open a terminal or command line on your computer and navigate to the directory where you want to store the repository.
Create a new repository on the command line:
```bash
mkdir new-project
cd new-project
touch README.md #add the initial text to it.
git init
git add README.md
git commit -m "init"
git branch -M main
git remote add origin git@github.com:vanelin/new-project.git
git push -u origin main
```

