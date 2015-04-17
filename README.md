# Github Workflow

### Step 1 - Forking the Repo
- Fork this repo by clicking the "Fork" button located on the top right of this page
    <br><img src="https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/fork-circle.jpg?raw=true" height='75'>

### Step 2 - Opening Command Line & navigating to your sandbox
The below describes steps to open up the command line in on a OSX ([Mac](https://github.com/Learning-Fuze/git-workflow#mac)) or Windows ([PC](https://github.com/Learning-Fuze/git-workflow#windows)). On a Mac the application we will be using is **Terminal** and the application on windows is **Git Bash**. We will be opening up the sandbox folder in the command line. <a href="https://docs.google.com/document/d/1GYqDtY12-RgzrbbHzY7kqxpqP_y_X6c5sNKH9NLqMPM/pub" target="_blank">Where is my sandbox Folder?</a>.

#### Mac - Option 1 (Right Click)
- If you have not done so already, enable [Easy osx terminal window opening](https://github.com/Learning-Fuze/git-workflow/blob/osx_easy_terminal/osx_easy_terminal.md)
1. Go to a folder in your finder 
	- ![Folder](https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/sandbox-finder.jpg?raw=true) 
2. Right click on the folder and look for **Services** at the bottom. Then select the option **New Terminal Tab at Folder**
	- ![Folder](https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/new-terminal-tab-finder.jpg?raw=true)

##### Mac - Option 2 (Direct Terminal Access)
1. Press the command key and space bar
	- You should see the spotlight search appear
	- type in Terminal and hit enter
2. Type in `cd ` (which stands for change directory) then drag your folder into the terminal window
3. For a computer user of "test" the line would look like this
	- `cd /Users/test/Desktop/sandbox`
	- *You should see "test" replaced with your computer username*
4. Hit Enter

#### Windows
1. Open windows explorer to the sandbox folder
2. Right click and select "Git Bash" as shown in the image below
	<br><img src="https://github.com/Learning-Fuze/git-workflow/blob/assets/assets/windows-git-bash-alt.jpg?raw=true" height="300">

### Step 3 - Cloning the repo
1. Type in the following into your command line 
	- `git clone https://github.com/your-user-name/git-workflow.git` and hit enter
		- **Note** The portion of the url that reads **your-user-name here** needs to change
		- The **clone** command tells git to save the contents of the master branch onto your computer within the current directory.
		- **Note**
			- Using the command above will automatically create a directory with the same name as the Repo. In this example **git-workflow**
			- The url after the word **clone** can be found in the right hand side panel of this page under the Settings link. You can click the button to the right of the url that will automatically copy this url for you
2. Then type `cd git-workflow` and hit enter
- Leave your console window open, we will be using it again shortly.

#### Congratulations you have cloned your Github Repository