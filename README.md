# devcontainer-setup
My initial dev container to explore the functionality and purpose of developement containers

Creating our first dev container in visual studio code:
Step one: 
-	Download docker desktop and install. Start it up and keep it running in the background. 
-	Download the Remote Development extensions in Visual Studio Code.
-	Create a new repository in git, add a readme file, and select python. 
-	Back in VS Code you can press Ctrl/Shift/P and type Dev to bring up a list of dev container commands. 
-	Select Dev Containers Clone Repository in Container Volume. 
-	Type in the git path of the repository we created earlier. In my case, it’s Nickl4242/devcontainer-setup.
-	Once it’s done you will have a prompt to add dev container configuration files. Here we can select some of the basic tools that we might want to be in our dev container. So for example if we wanted to do Azure development we can select that and get us started. We will be using the Default Linux Universal Container. It is a larger file but it's used for git hub code spaces and will have a large amount of tools for a whole list of different languages. 
-	For now, we won’t select any additional features. Click ok
-	This might take a while.
-	Okay let's pull down the .devcontainer file in the explorer and look at the json config file. 
-	
