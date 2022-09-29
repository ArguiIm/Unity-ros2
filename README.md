# Unity-ros2

This doc will have all steps needed to install and configure Unity + configure zed2 in Unity and Ros2.

## Git : 
git status
git add.
git remote add origin https://github.com/ArguiIm/Unity-ros2.git
git branch -M main
git push -u origin main

## Install Unity desktop :
- `sudo apt update`
- `sudo apt install ubuntu-unity-desktop`
- ` reboot`

## Install Unity :
- `sudo sh -c 'echo "deb https://hub.unity3d.com/linux/repos/deb stable main" > /etc/apt/sources.list.d/unityhub.list`
- ` wget -qO - https://hub.unity3d.com/linux/keys/public | sudo apt-key add -`
- `sudo apt update`
- `sudo apt-get install unityhub`
- `sudo apt-get remove unityhub` (to remove)