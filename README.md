# EaglerXVelocity
> Follow the step by step to use Velocity with EaglerXVelocity.
> I hope I made this idiot proof
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
 Paste this into the terminal then click enter:
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
### how to make 3 tabs
 ![Screenshot 2024-12-20 9 52 25 AM](https://github.com/user-attachments/assets/e7ca31b4-1303-4e09-b81c-978a25229135)
 click on the plus 2 times, then go back to the first tab
## Commands for server (backend)
 Paste this into the first tab then click enter:
```bash
cd server
./server.sh
```
## Commands for velocity (proxy)
 Paste this into the second tab then click enter:
```bash
cd velocity
./velocity.sh
```
## Commands for limbo (login)
 Paste this into the third tab then click enter:
```bash
cd limbo
./limbo.sh
```
# Port forwarding the server
 Go to where it says ports and click on it.
 ![Screenshot 2024-12-20 10 22 05 AM](https://github.com/user-attachments/assets/e86b821a-165c-4792-9693-e79408894aba)
 
## FAQ

#### How to turn off the Github Codespaces?

1.) Go to https://github.com/codespaces

2.) then click the 3 dots and turn off
