

1. First I have brought/created a free tier AWS Linux server using AWS console and connected through following 
command:

   $  ssh -i "bangal.pem" ec2-user@ec2-18-207-215-164.compute-1.amazonaws.com

2. nano already installed in the Linux. Confirmed by following command:

   $ nano --version
3. git is not installed in Linux server. git is installed by following command:

   $ sudo yum install git
4. git version is checked by the command

   $ git --version
5. QAAEB2201 Github repo is cloned by the following command under user directory and confirmed by executing
"ls" command:

   $ git clone https://github.com/Jahidul2543/QAAEB2201.git

   $ ls

   QAAEB2201

6. Under user directory one directory named "app" is created. Then copied all file and folders from cloned repo 
QAAEB2201 into app directory.   

   $ mkdir app

   $ cp -r QAAEB2201/* app

   $ ls QAAEB2201/

   cleanup_script.sh  MyApp  output.txt  WorkList.txt

   $ ls app/

   cleanup_script.sh  MyApp  output.txt  WorkList.txt
7. Screen capture is as Evidence of previous work of serial number 6
8. Few more commands are practiced on the server.

