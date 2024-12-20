# EaglerXVelocity
> Follow the step by step to use Velocity with EaglerXVelocity.

## Making the Github Codespaces with 16GB RAM and 4CPUs
To make the codespaces, make sure to access from https://github.com/codespaces.

# Installing Java(only once)
Paste this command into the terminal and wait until its done installing then move on to the next step:
```bash
sudo apt update -y & sudo apt full-upgrade -y & sudo apt autoremove -y & sudo apt auto-clean -y
```
Paste this command into the terminal and move to next step after its done:
```bash
sudo apt upgrade -y
```
Copy and Paste this into the terminal and wait until it says "Do you want java 17.0.9-amzn to be set as default? (Y/n)" 

and write "y" without the "" and MAKE SURE TO WRITE y
```bash
sdk install java 17.0.9-amzn
```

# Setting Up Server
 Paste this into the terminal
```bash
cd server
chmod +x server.sh
cd
cd /workspaces/EaglerXVelocity/velocity
chmod +x velocity.sh
cd
cd /workspaces/EaglerXVelocity/limbo
chmod +x limbo.sh
cd
cd /workspaces/EaglerXVelocity/
```
# How to turn the server back on (do this for everytime)
## Commands for server (backend)
```bash
cd server
./server.sh
```
## Commands for velocity (proxy)
```bash
cd velocity
./velocity.sh
```
## Commands for limbo (login)
```bash
cd limbo
./limbo.sh
```
## FAQ

#### How to turn off the Github Codespaces?

1.) Go to https://github.com/codespaces

2.) then click the 3 dots and turn off
