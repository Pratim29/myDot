How to Install Tor Browser in Kali Linux.

1) Download the latest .tar.xz file from the official Tor Project Website. https://www.torproject.org/download/
2) Verify the file's signature. This process should not be skipped. It let's us verify whether or not the file is coming from the right source. Guide on how to verify signature https://support.torproject.org/tbb/how-to-verify-signature/
3) Extract the content of the file to somewhere it belongs for example Downloads folder in user's directory. For command line reference: $ tar -xvf [archive name] /home/$USER/Downloads/
4) Now, download the file "torbrowser-launcher.desktop" from this page and move it to application directory. For reference: $ wget https://raw.githubusercontent.com/diggajupadhyay/myDot/master/Kali/.local/share/applications/torbrowser-launcher.desktop; mv torbrowser-launcher.desktop $HOME/.local/share/applications/
5) Restart or Logout and Log back in to see Tor Browser Launcher appear in Menu. 
6) Congratulation! You have done it.

Few tips: Make sure you are always using the latest and stable version rather than outdated or beta version which can cause serious security hole if you don't consider. Also, make the .desktop file executable. Always connect to bridge whenever connecting to Tor Networks. Last but not least, NEVER skip the verification step!  
