# Terminal in Windows 

For Windows users, using the terminal is not as easy as it is for Linux and Mac OS users.
By default, the Windows shell is the "Command prompt", which can be quickly accessed by
typing these two words in the search bar of your desktop (i.e. Ask Cortana).

However, this shell does not work like the bash shell, hence having different
commands from the ones you are going to be learning in this UNIX introduction.

Therefore, we have thought of three alternative ways to install a bash shell in your Windows OS.
Choose the one that best suits your preferences!

## 1. GitBash for Windows
You can install the GitBash for Windows, which can be downloaded from
[here](https://git-scm.com/download/win). Note that when you click this link, the 
download will automatically start.

If you are unsure which options you should allow during the installation,
you can follow the next recommendations:

<p align="center">
  <img width="700" height="500" src="https://github.com/sabifo4/RnBash/blob/master/figs/00_Winsteps1-4.png">
</p>

*Note that in **step 3** you can choose any of the text editors listed there to set it as the default text editor for the GitBash terminal. We recommend using* `nano` *as it is the simplest text editor listed there that you can use from the terminal. For the next steps, we just recommend carrying on the installation with the default options* 

<p align="center">
  <img width="700" height="500" src="https://github.com/sabifo4/RnBash/blob/master/figs/01_Winsteps5-8.png">
</p>
<p align="center">
  <img width="600" height="250" src="https://github.com/sabifo4/RnBash/blob/master/figs/02_Winsteps9-10.png">
</p>

Once the installation is finished, you will see the following icon in your Tasks bar,
which means that you will have the GitBash terminal installed!

<p align="center">
  <img width="100" height="100" src="https://mccarter.gallerycdn.vsassets.io/extensions/mccarter/start-git-bash/1.2.1/1499505567572/Microsoft.VisualStudio.Services.Icons.Small">
</p>


The coolest thing about this terminal is that you can manage Git
repositories (cloning repos, removing and adding files, etc.)
with simple Git commands. If you are thinking of becoming a GitHub user,
this is your terminal! You might also want to install
PuTTY to generate your SSH key. Visit [this website](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) and then download the 
`MSI ('Windows Installer')` (32-bit or 64-bit, depending on your OS) - click the corresponding link inside 
the first box entitled `Package files`. Alternatively, you can click 
[here](https://the.earth.li/~sgtatham/putty/latest/w64/putty-64bit-0.70-installer.msi) to automatically start the download.
If you want more information about this last step and how to correctly install 
PuTTY, then you can follow [this tutorial](https://www.siteground.com/kb/How_to_generate_an_SSH_key_on_Windows_using_PuTTY/).

## 2. Install a Linux distribution in a Virtual Box (VB)
If you are keen on having a complete Linux experience and want to have more than a terminal on a Windows OS,
you can always have your own Virtual Box with a Linux distribution.

We recommend you to download the [Virtual Box from Oracle](https://www.virtualbox.org/), 
install it in your PC, and then download your preferred Linux distribution. For instance, if you want to install Ubuntu, you can download the Ubuntu desktop from [here](https://www.ubuntu.com/download/desktop). Once you have installed the
VB and downloaded the Linux distribution, just follow the
instructions [here](http://www.psychocats.net/ubuntu/virtualbox). 
This tutorial explains how to install Ubuntu in the VB, but the same procedure
can be followed to install any other Linux distribution :smile: 

## 3. Get the Linux subsystem for Windows

### **WARNING: DO NOT DO THIS IF YOU ARE NOT COMFORTABLE/EXPERIENCED ENOUGH WITH THE COMMAND LINE NOR WITH ACTIVATING THE DEVELOPER MODE**
#### **--If you feel you might struggle to install the Linux subsystem but you really want to have it, please ask us any questions in the google group so we can assist you--**

The last option, which is available for only Windows 10 users, consists of
installing a Linux environment as a subsystem inside your Windows.
According to the [Documentation](https://docs.microsoft.com/en-us/windows/wsl/about), you can:

* Install your preferred Linux distributions.
* Run command-line utilities (e.g. `grep`, `sed`, `awk`, `sort`, etc.)
* Run bash shell scripts and Linux command-line applications such as tmux or vim.
* Choose your favorite Linux distributions from the Windows Store.
* Install Linux tools using (e.g. you can use `apt-get` as in Ubuntu)
* *... and many more - Check the documentation for more info*

You can follow [this tutorial](https://docs.microsoft.com/en-us/windows/wsl/install-win10) or 
[this one](https://www.onmsft.com/news/how-to-install-windows-10s-linux-subsystem-on-your-pc) to
install it. Note that now `Ubuntu` is also available from the Microsoft store. You can look for your 
preferred Linux distribution in the Microsoft store app (e.g., if you want `Ubuntu`, just type "Ubuntu" (no quotation marks) 
in the Microsoft store) and just follow the instructions on the screen to install it.

**NOTE:** If you have managed to successfully install the Linux subsystem on your Windows 
and would like to have a quick access to a terminal from any directory, 
please follow the instructions [here](https://www.windowscentral.com/how-launch-bash-shell-right-click-context-menu-windows-10).

--- 

# Terminal in Mac OS 

If you are a Mac OS user, you can launch a terminal
from which you can run UNIX/Linux commands. In general, most of the OS have the
bash terminal installed. You have an easy access to the terminal, but maybe 
you have never used this. 

Inside the `Applications` directory, you will find the `Utilities` directory. 
Go inside the latter and you will see one executable called `Terminal`. Double 
click and you will immediately launch the terminal! 

<p align="center">
  <img width="800" height="200" src="https://github.com/sabifo4/RnBash/blob/master/figs/03_Macsteps.png">
</p>

---

# Terminal in Linux distributions 

If you are a Linux user, you already have an easy access to the terminal
from which you can run UNIX/Linux commands. However, maybe 
you have never used it and you do not really know how to find it. Even the screenshots below show the steps you need to follow to find the terminal with interface from the Ubuntu 18.04 version, the same procedure applies to any other Ubuntu version or
Linux distribution. Just bear in mind that some of the buttons might be in a different place or 
the desktop interface might look differently, but the procedure to find and pin the terminal is very similar :smile:

Click the `Activities` button from the main menu and a search box will pop up
in the middle of your desktop. Then, start typing `terminal` there and you will see that immediately 
the terminal icon appears. If you click this icon, a terminal will open on
your desktop. Also, you will see that the terminal icon appears now in your tasks bar.
Right-click this icon and then select 
`Add to Favourites` to pin the terminal icon in your tasks bar. This will make your life easier to 
launch a terminal because you will not need to repeat the previous steps every single time you log in your session!
From now onwards, just click the terminal icon and start coding!

<p align="center">
  <img width="900" height="200" src="https://github.com/sabifo4/RnBash/blob/master/figs/04_Linuxsteps.png">
</p>


