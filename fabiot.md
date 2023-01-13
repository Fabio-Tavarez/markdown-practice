# Writing in Markdown

Below you'll find several sections with instructions. Inbetween the two comment tags marked "Start of Section #" and "End of Section #" complete the instructions for that section.

Check off each step as you complete it and [refer back to the reading](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) often to assist!

---

#### Section 1 Instructions
- [x] Add a level 2 heading called "Collaborative Programming"
- [x] Add a link to the collaborative programming reading, the link should say "What is pair programming?" 
- [x] Add a JavaScript code block that contains a jsdoc comment. Take one from a previous replit, use the one from the reading, or create a new one. 
- [x] Add a level 3 heading called "Pair Programming at Pursuit"
- [x] Make an ordered list of the reasons Pursuit wants you to pair program. This list should be bold.

---

<!-- Start of Section 1 -->
## Collaborative Programming
[What is pair programming?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/collaborative-programming)
```
/**
 * Creates a new car object from the gathered parameters.
 * @param {string} make - The make (or brand) of the car.
 * @param {string} model - The model (or generic name) of the car.
 * @param {number} year - The year the car was built.
 * @returns {Object} An object with `make`, `model`, and `year` keys.
 */
function createCar(make, model, year) {}
```
### Pair Programming at Pursuit
**1. Knowledge retention and sharing. It is inevitable that at some point another student will know more than you about a particular topic, and vice versa. Pairing gives you multiple opportunities to gain knowledge from other Fellows, or share that knowledge.**

**2. Focus. When you're working with another person, it's difficult to get sidetracked. Working with other Fellows will help both of you stay on task so that you can efficiently complete your assignments.**

**3. Expediency. When you're working with a pair, it's less likely that you will get stuck on frustrating problems like syntax errors. This is because you will have someone else looking on who will be able to spot your small mistakes. Instead, you'll get stuck on the larger, more difficult problems. And that's good! You want to spend your time working through misunderstandings, not spellchecking your variables.**

**4. Community. The students you work with could be your future coworkers, so it's important to have many chances to work with them. While pairing, you'll be developing your interpersonal and teamwork skills which are critical for your future roles.**
<!-- End of Section 1 -->

---

#### Section 2 Instructions
- [x] Add a level 2 heading called "Intro to the Command Line"
- [x] Add a link to the intro to command line reading, the link should say "What is the terminal?" 
- [x] Add a level 3 heading called "Keywords"
- [x] Re-create the list of keywords from the intro to command line reading, making sure to mark all code keywords as the reading did.
- [x] Add a level 3 heading called "Examples"
- [x] Create a bash code block containing the following examples, each example should have a code comment above it describing what it's doing:
    - Check your current file path
    - List the files and folders in your current directory
    - Make a directory
    - Navigate to that directory
    - Create a file within that directory
    - Move up one directory
    - Open a directory in Visual Studio Code
    - Open a directory in Finder
- [x] Add a level 3 heading called "Tips"
- [x] Recreate the tips section from the intro to command line reading
---

<!-- Start of Section 2 -->
## Intro to the Command line
[What is the terminal?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/intro-to-command-line)
### Keywords
- Operating System (OS)
- Graphical User Interface (GUI)
- Command Line Interface (CLI)
- Terminal
- Shell
- Folder = directory
- `pwd` - print working directory
- `cd ..` - go to parent directory (aka up)
- `cd [folder]` - go into folder
- `~` - represents your home folder
- `ls` - list files and subfolders in current folder
- `touch [filename]` - create a new file
- `mkdir [directory name]` - make a new directory
- `code [filename]` - open the VSCode editor

### Examples
```bash
#Check your current file path
pwd
#List the files and folders in your current directory
ls
#Make a directory
mkdir Example
#Navigate to that directory
cd Example
#Create a file within that directory
touch readme.md
#Move up one directory
cd ..
#Open a directory in Visual Studio Code
code Example
#Open a directory in Finder
open Example
```
### Tips

- Use tab to autocomplete. for example, if the current folder has subfolders titled `games`, `photos` and `photography`, typing `pho` and pressing the tab key will result in displaying `photo` and `photography`. If we then type the letter `g` to get `photog`,and press the tab key - the command will be autocomplete to `photography`.

- You can also use the up and down arrow keys to cycle through all the commands you've typed.

<!-- End of Section 2 -->

---

#### Section 3 Instructions
- [x] Add a level 2 heading called "Git"
- [x] Add a link to the git presentation that we covered in class, the link should say "Git, what is it good for?" 
- [x] Create a bash code block showing how to do the following:
    - Make a directory
    - Navigate to that directory
    - Initialize a Git Repo
    - Create a readme.md file
    - Check the status of the repo
    - Stage the readme.md file
- [x] Put together instructions, utilizing code blocks when necessary, describing the following steps:
    - Open the directory you created previously in Visual Studio Code
    - Update the readme.md file
    - Compare the differences between the staged and unstaged readme.md files
    - Stage the changes to the readme.md file
    - Commit the changes
---

<!-- Start of Section 3 -->
## Git
[Git, what is it good for?](https://docs.google.com/presentation/d/1KSqHQw8DxaZTtGQn5VKjP_Ljv4H_zc2hfE1CEVH8M8o/edit#slide=id.g420132f636_0_109)
```bash
#Make a directory
mkdir Example
#Navigate to that directory
cd Example
#Initialize a Git Repo
git init
#Create a readme.md file
touch readme.md
#Check the status of the repo
git status
#Stage the readme.md file
git add readme.md
```
 - Open the directory you created previously in Visual Studio Code
 ```
 code Example
 ```
 - Update the readme.md file
 - Compare the differences between the staged and unstaged readme.md files
 ```
 git diff
 ```
 - Stage the changes to the readme.md file
 ```
 git add readme.md
 ```
 - Commit the changes
 ```
 git commit -m "Initial Commmit"
 ```
<!-- End of Section 3 -->

---

#### Section 4 Instructions
- [x] Add a level 2 heading called "GitHub (YourGithubUsername)"
- [x] Add a link to the GitHub reading, the link should say "GitHub, Let's build from here"
- [x] Create a level 3 heading called "Connecting Local to Remote"
- [x] Create a level 4 heading called "Local vs. Remote"
- [x] Describe, in your own words, what the difference between a local repo and remote repo is. 
- [x] Create a level 4 heading called "Getting ready on your local machine"
- [x] Copy the above section from the GitHub reading and highlight the code snippets where necessary.
- [x] Create a level 4 heading called "Creating a new repository"
- [x] Create a list detailing how to create a repository on GitHub (use the GitHub reading)
- [x] Create a level 3 heading called "Push your code"
- [x] Copy the "Push Your Code" section from the GitHub reading and format it the same way.
- [x] Create a level 3 heading called "Collaborating with GitHub"
- [x] Create a step by step task list for the collaboration process. Include the following:
    - Forking
    - Cloning
    - Making Changes
    - Pull Requests

---

<!-- Start of Section 4 -->
## GitHub (Fabio-Tavarez)
[Github, Let's build from here](https://github.com/9-5-pursuit/unit-fundamentals/blob/main/github/reading/readme.md)

### Connecting Local to Remote

#### Local vs. Remote
The term "local" usually refers to your computer or any other device. Meanwhile "remote" refers to when something is stored somewhere else in this case GitHub. So a local repo is your copy of a repo that is stored on your machine. While the remote repo is a copy that is stored on GitHub for other to see and work on if needed.

#### Getting ready on your local machine
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

- Create a new directory with at least one file.

- Initialize that directory as a git repository with `git init`.

- Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.

#### Creating a new repository
- You can create a new repository from the GitHub.com homepage. Click the green New button to get the process started.

- Alternatively, you can click the "+" button in the top-right corner of any GitHub page. You will then be brought to a page where you can name your repository.

- You should give your repository a name that is meaningful as opposed to the nonsense names GitHub typically suggests, like "curly-rotary-phone." It's also typical to give your repository the same name as the folder that contains your repository on your local machine.

- At the bottom of the screen, it gives you the option to initialize your repository with some files. You will have already initialized your repository on your local machine, so you do not need to check these boxes.

- After clicking the "Create repository" button, you will be brought to a new page that includes a number of code blocks.

- Because you should have already created a repository, you'll be following the instructions under the heading "...or push an existing repository from the command line."

### Push your code

There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

**`git remote add origin <url>`**

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name could be whatever you want, but you can just leave it as origin.

**`git branch -M main`**

This command sets the name of the main "branch" to be called `main`. You will learn more about branches later on. For now, know that the `main` branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

**`git push -u origin main`**

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local `main` branch and git will know that you want to push to the `main` branch of the remote repository by the name of "origin".

### Collaborating with GitHub

- [ ] Fork a repository by clicking the Fork button at the top of any repository you have access to
- [ ] A new page will appear with some pre-filled settings. Click `Create Fork` to complete the forking process.
- [ ] Before we can clone your new repo, we need to get the link. Click the green `Code` button and copy the "https" link. 
- [ ] In your Terminal, navigate to the _parent_ directory where you want this repo to live and run `git clone <url>`
- [ ] Confirm your file was downloaded successfully by running `ls` - the new folder should be listed in the results
- [ ] Open the new folder in Visual Studio Code by navigating to it `cd [new directory]` and then running the code command like so: `code .`
- [ ] Now that your folder is open in Visual Studio Code, change one of the files, or add a new file, and save.
- [ ] Return to your Terminal and run `git status` - you should see an untracked change that matches the change you just made.
- [ ] Run `git add .` to add all of your changes to staging.
- [ ] Now commit these changes in your Terminal by running `git commit -m "A message describing what changes you made."`
- [ ] Open your GitHub page again and refresh it, you should see the changes you just made.
- [ ] Open a Pull Request by choosing the `Contribute` dropdown and clicking the `Open pull request` button. 
- [ ] Add a title (this may be prefilled) and any additional comments.
- [ ] Click the `Create pull request` button. Confirm the request if necessary.

<!-- End of Section 4 -->

---

#### Section 5 Instructions
- [x] Add a level 2 heading called "My Time at Pursuit"
- [x] Add an image that represents your time in the program so far.
- [ ] Add a list with the following 3 things:
    - One thing you need to work on
    - One thing you feel you understand well
    - One thing you are looking forward to learning
- [ ] Create a to-do list for your long weekend
- [ ] Add a quote that keeps you motivated to keep pushing.
- [ ] Add a paragraph of bold text describing who you're doing this program for and why.
---

<!-- Start of Section 5 -->
## My Time at Pursuit
![This is an image](https://knowyourmeme.com/photos/1401347)

- One thing I need to work is to better at is understanding technial terms relating to GitHub
- One thing I understand well is Javascript
- Looking forward to learn html and css
- [ ] Get the homework done on time
- [ ] Do the reading and take notes
- [ ] Get some practice in
- [ ] Enjoy the weekend
> The only guarantee for failure is to stop trying.

**I'm doing this program for two people my Mom and I. The reason for this is to give us a better standard of living.**
<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request