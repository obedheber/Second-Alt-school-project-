# Second-Alt-school-project-
This documentation is about how I provisioned my server, installed the web server, deployment of the HTML page and configured networking step by step.
# Provisioning of the Server
Using Cloud provider, AWS to set up a Linux server,

* I installed a Linux distribution "GIT BASH" on my HOST machine (WINDOWS)

* I installed a web server Apache to serve as a web content on GIT BASH

# Installation of the Web Server
After the provisioning of the server

*I ran the command sudo apt update to update and ready all new available applications,

*Then I ran sudo apt install apache2 to install the Apache2 web server.

Apache2 is ready for hosting

# Deployment of the HTML Page

*Using VS code, I wrote a simple HTML page 

*Inside my Linux Server, I copied the content of my HTML page into the apache test file

*I copied public IP address from my EC2 instance in the AWS console , which is inet 54.174.248.133

*Then I pasted the public IP address inside my browser which did not show the content of the HTML page due to the network not being configured.

# Networking Configuration

*Under AWS console i clicked on Network and Security then under it i clicked inbound rules after which clicked on edit inbound rule.

*Then i add a new rule by selecting "Custom TCP", set the port to "80", then the IP to "Anywhere IPv4" and i saved the rule.

# The Public IP Address.

Public Ip address:54.174.248.133

# Screenshot

!(img alt) https://github.com/obedheber/Second-Alt-school-project-/blob/a5567700799451c253b45a6b05575ca873d35ba0/screenshot.md




