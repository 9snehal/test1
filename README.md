king a Web Server file:
A simple web server file here in the webpage take input from you and after click on submit button they print the output.
 

### How to run this code:

1.Install the VM and Vagrant:
This project uses a virtual machine (VM) to run a SQL database server.

2.If you don't already have virtual box on your machine, you can download it here:
->https://www.virtualbox.org/wiki/DownloadOldBuilds51 
or for ubuntu type this command: sudo apt-get install virtual box

3.Download and install Vagrant (if you do not already have it installed). This is the software that configures the VM and allows the host (your machine) to talk to the VM:
-->https://www.vagrantup.com/
or for ubuntu type this commnad: sudo apt-get install vagrant
->you should be able to run $ vagrant --version after installation to see the version that was installed.

4.Download and unzip this file:https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5acfbfa3_fsnd-virtual-machine/fsnd-virtual-machine.zip  This will give you a directory called FSND-Virtual-Machine. It may be located inside your Downloads folder.

Alternately, you can use Github to fork and clone the repository https://github.com/udacity/fullstack-nanodegree-vm.

5.cd into this(FSND_Virtual_Machine) directory

6.cd into the vagrant/ subdirectory

7.Bring the VM up with the command vagrant up

8.Log into the VM with vagrant ssh

#Download and run the file
1.Clone this repository to your local drive: https://github.com/9snehal/test1

2.Copy the  file into the FSND_Virtual_Machine/vagrant directory.

3.Open a terminal window from the FSND_Virtual_Machine/vagrant directory, or simply open a terminal window and cd into that directory.

4Run vagrant ssh at the prompt to log in to the VM.
$ vagrant ssh

5.cd into the vagrant subdirectory
vagrant@vagrant:~$ cd /vagrant

6.Run the webserver.py program
vagrant@vagrant:/vagrant$ python webserver.py

7.Open the browser and run the 'localhost:8080/hello' as per given in the file

8.The program's output will be displayed in browser.



