# Git & Markdown
Here’s a quick look at using Git and Markdown. Git, in short, is a version control system that’s meant for handy tracking of changes and work coordination. Markdown is a markup language with plain text formatting syntax. It is designed so that it can be converted to HTML and many other formats using a tool by the same name. In the following task, I’ll use both of these in a brief fashion. 

This post is part of a server management course I’m attending, [taught by Tero Karvinen.](http://terokarvinen.com/2018/aikataulu-%E2%80%93-palvelinten-hallinta-ict4tn022-4-ti-5-ke-5-loppukevat-2018-5p)

# Markdown
The markdown version of this report can be found here: https://github.com/oliverlahti/markdown/edit/master/README.md

# Using Github for SaltStack states
In an earlier task I made a repository on my Github account, called “school“. In this, I placed a “high.sh” file that included a local saltstack state.highstate command, to be executed with bash. The top file uses a state that creates an empty text file. I wanted to clone the repository to my virtual PC, so I used the command “sudo apt-get install -y git” and “git clone https://github.com/oliverlahti/school” to install Git and clone my repository:
![alt text](https://oliverlahti.files.wordpress.com/2018/05/1.png "1")
![alt text](https://oliverlahti.files.wordpress.com/2018/05/2.png "1")

After the successful cloning, I executed the top file with “sudo bash high.sh“. The creation of the text file went perfect:
![alt text](https://oliverlahti.files.wordpress.com/2018/05/3.png "1")

Using repositories with Git is really easy, as you can see!
# Sources:
http://terokarvinen.com/2018/aikataulu-%E2%80%93-palvelinten-hallinta-ict4tn022-4-ti-5-ke-5-loppukevat-2018-5p – The course I’m attending

https://en.wikipedia.org/wiki/Markdown – Markdown Wikipedia page
