# command-Line Basics - week2
This README contains the git commands I used during this week's assignment and their outputs.
## initialize a git repository
'cd projects' - to move into the projects folder from week1
output: confirms 
'git init' - to initialize or set up a new git repository in the projects folder which allows git to track changes.
## Add and commit files
'git add .' - stages all files for the next commit
'git commit -m "initial commit" - saves the staged changes with a message.
## Push to github
I created a new repository named 'my-first-project manually on github
'git remote add origin https://github.com/graciousjoe/command-line-basics/blob/main/my-first-project' - connects the local repository to github
'gitpush -u origin main' - sends the committed files to github
## practice cloning
'git clone https://github.com/graciousjoe/command-line-basics/blob/main/my-first-project' - downloads a copy of the repository to a new location
## modify and push changes
'touch goals.txt'  - to add a new file named goals.txt
'echo "my programming goals(cloud computing specifically): 1. learn the basics of cloud platforms-AWS, Azure or Google cloud.
'echo "2. Deploy a simple cloud application -  host a website or service using cloud resources."
'echo "3. Understand cloud security and networking."
creates and adds text to the goals.txt file
'git add goals.txt' - to add the file to github
'git commit -m "Added my programming goals(cloud computinng specifically)"
'git push origin main' - uploaded it to main branch on github
