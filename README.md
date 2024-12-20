# EaglerXVelocity
> Follow the step by step to use Velocity with EaglerXVelocity.
> 
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

 If you completed the steps above as intended then it should have 3 auto-forwarded ports, 8081, 25565, and 25577.
 Right click on 8081 then click port visibility, and click on public.
 Right click on 8081 again then on "Open In Browser" it should tell you the server ip.
## FAQ

#### How to turn off the Github Codespaces?

1.) Go to https://github.com/codespaces

2.) then click the 3 dots and turn off

#### How do I add plugins?

1.) Go to [Spigot](https://www.spigotmc.org/resources/categories/spigot.4/) or [Bukkit](https://dev.bukkit.org/bukkit-plugins)

2.) Download a plugin of your choice(make sure it supports 1.8) go to your codespace server, open the "server" folder then drag (plugin).jar into the plugins folder inside the server folder.

3.) Type "restart" on the first tab. Type pl in the first tab and it should say Plugins(#) (plugin), if it doesn't then delete it from the plugins folder and repeat the process.
