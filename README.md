root@web3-VirtualBox:~/shriram# rm ~/.ssh/id_ed25519.pub
root@web3-VirtualBox:~/shriram# rm ~/.ssh/id_ed25519.pub
rm: cannot remove '/root/.ssh/id_ed25519.pub': No such file or directory
root@web3-VirtualBox:~/shriram# ssh -keygen -t ed25519 -C"shrirameddy700@"^C
root@web3-VirtualBox:~/shriram# tree
.
└── key.txt

0 directories, 1 file
root@web3-VirtualBox:~/shriram# git init^C
root@web3-VirtualBox:~/shriram# ssh -keygen -t ed25519 -C "nowto"
Bad escape character 'ygen'.
root@web3-VirtualBox:~/shriram# ssh-keygen -t ed25519 -C "nowto"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/root/.ssh/id_ed25519): key.txt
key.txt already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in key.txt
Your public key has been saved in key.txt.pub
The key fingerprint is:
SHA256:gv9lSTOdhdb38/8IRpAUPyB0RoPIT59XKF2LVB4VY78 nowto
The key's randomart image is:
+--[ED25519 256]--+
|     . oooOo.++=o|
|      o o=.*o=ooo|
|       o .oo*.= o|
|     .  . o+.+ .o|
|    . . S +.+  E.|
|     . . . =    o|
|      .   + o   .|
|       . o . . ..|
|        .     . +|
+----[SHA256]-----+
root@web3-VirtualBox:~/shriram# cat ~/.ssh/id_ed23319.pub
cat: /root/.ssh/id_ed23319.pub: No such file or directory
root@web3-VirtualBox:~/shriram# cat ~/.ssh/id_ed25519.pub
cat: /root/.ssh/id_ed25519.pub: No such file or directory
root@web3-VirtualBox:~/shriram# gedit key.txt

(gedit:3223): Tepl-WARNING **: 11:53:16.388: GVfs metadata is not supported. Fallback to TeplMetadataManager. Either GVfs is not correctly installed or GVfs metadata are not supported on this platform. In the latter case, you should configure Tepl with --disable-gvfs-metadata.
root@web3-VirtualBox:~/shriram# mkdir -p ~/.ssh
root@web3-VirtualBox:~/shriram# mv key.txt ~/.ssh/id_ed25519
root@web3-VirtualBox:~/shriram# mv key.txt.pub ~/.ssh/id_ed25519.pub
root@web3-VirtualBox:~/shriram# cat ~/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAILtcWTbH7fHOKDF16kCYqW9eYbrtCMNZ0/bLaqzFnIzk nowto
root@web3-VirtualBox:~/shriram# ssh -T git@github.com
ssh: connect to host github.com port 22: Connection timed out
root@web3-VirtualBox:~/shriram# ssh -T git@github.com

ssh: connect to host github.com port 22: Connection timed out
root@web3-VirtualBox:~/shriram# 
root@web3-VirtualBox:~/shriram# 

