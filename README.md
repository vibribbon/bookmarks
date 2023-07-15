# bookmarks

Load bookmarks from a simple dmenu, bmark for normal shared bookmarks, and optional bmarkp for personal bookmarks.  
Set to a shotcut for easy operation.
place bookmarks in ~/bookmarks.txt, personal bokmarks in ~/bookmarks_personal.txt

All scripts are without any kind of warranty, use entirely at your own risk!

On linux place into /user/local/bin/ and change permissions as follows: 
sudo chown root /user/local/bin/bmark.sh 
sudo chmod 755 /user/local/bin/bmark.sh 
sudo mv /user/local/bin/pcinfo.sh /user/local/bin/bmark

sudo chown root /user/local/bin/bmarkp.sh 
sudo chmod 755 /user/local/bin/bmarkp.sh 
sudo mv /user/local/bin/pcinfo.sh /user/local/bin/bmarkp

Dependancies: dmenu
sudo apt-get install dmenu
The Dmenu project is located here: https://tools.suckless.org/dmenu/

This tool is designed to be terminal only and extremely small with few dependencies. Some components do not work on weyland currently.

END
