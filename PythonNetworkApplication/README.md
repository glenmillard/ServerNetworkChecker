#Python Networking Project

TODO -explain how the project works
TODO - explain what each file means
TODO - not fully baked yet.
TODO - list what Python modules/libraries you will need that are not built in - for now, see the import statements in the scripts.

Files to note:
1. cmd.txt - this contains the commands that you want to run on all of your servers (yes, I know you can do this with Ansible!)
2. cpu.txt - this saves the output of your commands for futher use - see below.
3. ip.txt - these are the ip address(es) of your servers
4. user.txt - this contains your username and password

So, how do I use this?
1. Clone this repo - https://github.com/glenmillard/ServerNetworkChecker.git
2. create a few virtual machines - maybe 3
3. add your creds to the user.txt, the commands you want to run on your servers to cmd.txt, and your ip.txt - put the ip addresses of your servers.
Run the NetworkApp.py script - it will prompt you for the location of your files
once your application is up and running, run the graph.py script - this will show you the CPU load of your server(s)