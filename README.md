# termux-login
Termux password protected script with jarvis sound



 [+] Information :

   Termux is a Android emulator we can run many kali linux
   tools in termux (android) so here i am created a small 
   python script which works as a login form.means it lock
   your termux app when you are open termux it ask you to
   enter username and password.if you guys enter right 
   username and password the termux will open means you can
   use termux otherwise if you dont enter user and pass
   this script will close your termux app. so hope you like
   that .in futere i will make this script more secure/
   

   Termux-login

[+] warning :- if anybody want to modify this script and want to 
    upload on own github then you guys make sure to give my original github link on your README.md as a credit..okk

[+] install and use
  
    git clone https://github.com/A4k4sh/termux-login.git

    cd Termux-login

    mv log.py $HOME
    mv terminal.mp3 $HOME

    Now you want autorun this log.py so follow this

    cd ..
    cd usr/etc/
    nano bash.bashrc
    (here type) python log.py
    mpv /$HOME/terminal.mp3

    press ctrl + x and then y to save.

    Now open Your Termux this script is autorun and secure termux.


