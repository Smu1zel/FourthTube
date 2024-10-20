You need:

 - devkitPro with devkitARM r58  
 - ```3ds-zlib``` and ```3ds-mbedtls``` installed in portlibs of devkitPro  
   You can install it by opening devkitPro msys2 and typing ```pacman -S [package name]```.

Type ```make``` in a  terminal in the root directory (if you are on Linux) or ```make all_win``` (if you are on Windows) to build it.  

 - Building of dependency libraries(optional)  
   For ffmpeg, libbrotli, and libcurl, follow built.txt in each directory  
   For libctru, just type ```make``` in library\libctru\source\libctru  