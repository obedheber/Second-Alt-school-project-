# Second-Alt-school-project-
This documentation is about how I provisioned my server, installed the web server, deployment of the HTML page and configured networking step by step.
# Provisioning of the Server
Using virtualization to set up a Linux server,

*I installed a Virtual Machine (Virtual Box) on my Host Machine (Windows),

*I downloaded and installed vagrant_2.4.1_windows_amd64 which is meant for windows,

*Using Termius, I created a repository (mkdir repo) and cd into the repository to set up vagrant with Ubuntu 20.04 LTS also called focal 64 (an ISO image/Linux distribution),

*I ran the command vagrant init focal/64 to initialze the vagrantfile inside the repository created and in the virtual box,

*Then I ran command vagrant up to start up my server (Ubuntu 20.04 LTS) which is now being installed inside my virtual box,

*Then command vagrant ssh to enter the server.

# Installation of the Web Server
After the provisioning of the server (still inside Termius)

*I ran the command sudo apt update to update and ready all new available applications,

*Then I ran sudo apt install apache2 to install the Apache2 web server.

Apache2 is ready for hosting

# Deployment of the HTML Page

*Using VS code, I wrote a simple HTML page 

*Inside my Linux Server, I copied the content of my HTML page into the apache test file

*I ran ifconfig command to see the public IP address, which is inet 54.174.248.133

*Then I pasted the public IP address inside my browser which did not show the content of the HTML page due to the network not being configured.

# Networking Configuration



