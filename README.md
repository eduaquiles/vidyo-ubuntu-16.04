
# update vidyo installer to work with ubuntu 16.04

from: https://askubuntu.com/questions/766615/how-to-install-libqt4-core-and-libqt4-gui-on-ubuntu-16-04

# steps:

1. clone this repo
2. grab vidyo installer from somewhere
3. run the script
4. replace the line:

   ```Depends: libxss1,libaudio2,libasound2,libqt4-gui (>= 4.8.1), libqt4-network```

   with

   ```Depends: libxss1,libaudio2,libasound2,libqt4-designer,libqt4-opengl,libqt4-svg,libqtgui4,libqtwebkit4,libqt4-network```
5. install the .modified.deb file
