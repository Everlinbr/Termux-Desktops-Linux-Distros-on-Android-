# Termux-Desktops(Linux-Distros-on-Android)
This File is created to Explain how to install some Linux-Distro with GUI in Android
                                                                             ~Everlinbr
---                     
## Introduction          
Hello Everyone who is reading/viewing this repository,I am Everlinbr
and with the help of this repository i will tell you how to install different
Linux-Distros with GUI using Termux and Termux:X11
I am also writing this repo using Termux Native Desktop with Code-Oss

## First Step
First of all you will need to install Termux by clicking on link or using F-Droid  
**Installing Necessary pkg and Dependencies**  
After that you will need to install some important pgks in Termux and the command needed to install them are given below, you will just need to copy paste them into Termux   
   `pkg update && pkg upgrade`  
This cmd will update your Termux Internal Packages to latest version  
   `pkg insxtall x11-repo`   
This cmd will install X11-Repository that will allow you to run GUI with the help of an app named Termux:X11   
   `pkg install termux-x11-nightly`   
This cmd will install the Basic packages needed to run Termux:X11   
   `pkg install tur-repo`    
This cmd will install 'tur-repo' or 'Termux-User Repository' which contains many popular applications built specifically for Termux like Code-oss(De-Microfted Vs-Code for Termux),GIMP(A Photo editing/manupulation Tool),Chromium(De-Google Chrome but very lightweight),etc   
   `pkg install pulseaudio`   
This cmd will install Pulseaudio that will help us to hear the sounds that run inside Termux   
   `pkg install proot-distro`    
This cmd will install Proot-Distro that will help us to run some Linux-Distro and there is also another software for this that is called 'Chroot' that needs a Rooted Device(It is a unlocked device in which we can intefere with the system code or run any other OS) to run.    
   `pkg install wget`    
This cmd will install wget that can download anything from the Internet with the help of its URL    
   `pkg install git`    
This will install Git that can download or Copy and Repository from Github    
**Difference b/w Proot,Chroot and Installed OS**    
Proot-    
*This installs an Linux-Disto inside Termux and creates a Sandbox that can run the OS,it the OS that it is a Supported Device that in which you are running.It cannot utilise the Hardware of the Device,to utilise the Hardware we will need to setup an Extra Server that will utilise the Hardware of your Device*    
    
Chroot-    
*This installs an Linux-Disto inside Termux and run the OS with the main OS,its like having 2 different OS in a Single Device.It utilises the Hardware of your Device without the setup of an Server to utilise the Hardware*   
  
Installed OS-    
*This can be any OS that is running on your Device like Windows,Android,Linux,MacOS,etc.These OS are pre-installed on your Device and cannot be Changed or Removed easily.They utilise the Hardware bcz. they are the ones that lets you use that Device*    
### Installing Linux-Distros using Termu
