# # sudo apt-get update
# sudo apt-get upgrade
# sudo apt-get install gradle

Install Java:
sudo apt install default-jdk
sudo nano /etc/environment

Add following lines to file to set Java environment variables
JAVA_HOME=/usr/lib/jvm/default-java
PATH="$PATH:$JAVA_HOME/bin"

# update-alternatives --list java
Copy and replace dir on terminal:
# update-alternatives --set java /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java


Installing Android Studio:
Download latest version Android studio from
https://developer.android.com/studio/index.html
# unzip 
sudo unzip android-studio-ide-141.2178183-linux.zip -d /opt
sudo -xpf file.zip /opt

sudo apt-get install lib32z1 lib32ncurses5 lib32bz2-1.0 lib32stdc++6
Or
sudo apt-get install lib32z1 lib32ncurses5 lib32stdc++6

Execute Android Studio:
sudo /opt/android-studio/bin/studio.sh
Or
cd /opt/android-studio/bin
bash studio.sh

Execute script:
# git clone https://github.com/Hack-BitGod/WhatsAppHacking.git
# cd whatshack/
# ./whatshack.sh

To Execute Whatsapp Crasher
# python3 WhatsAppCrasher.py








