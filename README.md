# android-py-coding

Setting up Android for Python coding

Step-By-Step instruction:

  Step 1: Download Termux.
    
    You can download it from Google Play and from Termux.apk from this repository
    
    Google Play: https://play.google.com/store/apps/details?id=com.termux
    From repo: https://github.com/Linuxoid-git/android-py-coding/raw/master/Termux.apk (you will need to install Termux from downloaded .APK)
  
  Step 2: Install Git.

    Open Termux.
    
    Now we have to install Git
    
    Run this command to install Git:
      
      pkg install git
     
    Done!
   
  Step 3: Clone this repository.
  
    Now we need to clone this repository.
    
    Run this command for it:
    
      git clone https://github.com/Linuxoid-git/android-py-coding.git
      
    Done!
    
  Step 4: Install Python.
  
    Go to our repo using:
    
      cd android-py-coding/
      
    Now you need to choose - what version of Python you want to install.
    
    To install Python 3 run this command:
    
      sh py3inst.sh
    
    To install Python 2 run this command:
    
      sh py2inst.sh
    
    Done!
     
  Step 5. Test Python:
  
    For testing Python 2 run this command:
    
      python2 pytest.py
      
    For testing Python 3 run this command:
    
      python3 pytest.py
    
    Done!
    
Extra info:

  For working with any text files we need text editor. The best text editor for Termux is nano.
  
  To install nano run: 
  
    pkg install nano
    
  To edit file with nano run:
  
    nano <filename>
    
  nano GUI is very simpy. There's main features
  
    CTRL + O - to save file
    
    CTRL + G - to get help
    
    CTRL + X - to exit
  
  Also for working with any files and projects directories is required.
  
    To make new directory run:
    
      mkdir <directoryname>
    
    To go to your directory run:
    
      cd <directoryname>
      
    To go out of the directory run:
    
      cd ..
  
    To see which files and directories are in the current directory run:
    
      dir
      
  Note: Before starting some new projects go out of the repository directory and remove it:
  
    To remove files run:
    
      rm <filename>
      
    To remove directories run:
    
      rm -r <directoryname>
    
    For moving files or directories run:
    
      mv <from> <to>
    
Good luck!
    
  
  
   
    
        
    
        
  
  
