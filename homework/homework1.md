##Homework \#1:
=============

**Due: November 2nd, 2014** at 11:59pm

####Part 1: Join the GitHub team

1. If you haven't already done so, create a GitHub account. It's free!
2. Go to this URL: https://github.com/SSC-HoCgroup/Git-Demo
3. In order to contribute to our project, you must first join our team. To do so, either:
  * "Watch" the project (click on the "Watch" button in the top right corner of the screen) *or* 
  * [E-mail me directly](mailto:mollyawatson@gmail.com) with your GitHub username

**Note: Don't skip Part 1! You won't be able to participate in this homework unless you've been added to the team.**

####Part 2: Get Git Setup

1. Install Git on your home system / primary development system using **one** of the following links:
	* Download a compatible version of Git for your system: http://git-scm.com/downloads
	* Download a Desktop client for your system: [Mac](https://mac.github.com/) | [Windows](https://windows.github.com/)
2. Walk through the Try Git Tutorial at least once: https://try.github.io/levels/1/challenges/1
3. Download this handy list of commonly used Git commands: https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf
4. Set up your global variables, using the following commands:
	* ```git config --global user.name "Your Full Name"```
	* ```git config --global user.email "Your email address"```

####Part 3: Get the Git-Demo files

1. Decide on a location on your computer where you can download the Git-Demo repository
2. Navigate to that folder in Terminal (Mac) or Command Line (Windows), or use one of the Desktop clients.
3. Create a new git repository in that location by using the command:
	* ```git init```
4. Create a link to the remote GitHub Git-Demo repository by using the command:
	* ```git remote add git-demo-origin https://github.com/SSC-HoCgroup/Git-Demo```
5. Copy the remote Git-Demo repository's code to your computer using either one of these commands:
	* ```git pull git-demo-origin master``` *or*
	* ```git clone https://github.com/SSC-HoCgroup/Git-Demo/```

***Note:*** *if you use 'git clone', a new folder will appear in your repository called "Git-Demo" containing the repository's files, whereas using 'git pull' will directly copy the repository's files into your current directory.* 

####Part 4: Participate and practice Git!

1. After downloading the repo's files, go to the folder titled 'introductions' and create a new text file. Title the file with your name (ex: molly-watson.txt).
2. Fill the file with the following information (see introductions/molly-watson.txt for examples):
	* Name:
	* Short Bio: 
	* Coding / Tech Interests:
	* Message for the group:
3. Next, open the file in the main Git-Demo repository titled 'participants.txt', and add your name to the bottom of the list. 
4. In the Terminal / Command Line program, use the 'git status' command to check the state of your files. You should see that there is one new untracked file, and one new modified file.
5. Add / update these files by using the 'git add' command, like so:
	* ```git add introductions/your-name.txt```
	* ```git add participants.txt```
6. Run 'git status' again to make sure that your files will be included in the next commit you make.
7. Commit your changes! Use the command:
	* ```git commit -m "Adding my information to participants and introductions - YOUR INITIALS"```
8. Next, before you push to our repo, first do a 'pull' to make sure your repo is up-to-date.
	* ```git pull git-demo-origin master```
9. Lastly, push your changes to our repo! Use the following command: 
	* ```git push git-demo-origin master```
	* When you run this command, you will need to enter your GitHub username and password in order to proceed
	* **Note:** If you have not been added to our team (Part 1, \#3), you will receive an "Permission Denied" error from GitHub. If this happens, let me know: [send me an email](mailto:mollyawatson@gmail.com).
