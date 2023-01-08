# kivy-recipes-for-make && warning: JUST FOR PYTHON2 

> Step 1: 
>> Get this zip file it down and put them into a directory.

> Step 2:
>> Move to this directory and make it work like a website service,you can use this command,below:
```shell
cd /tmp/android-recipes/ && python -m SimpleHTTPServer 80 &
```
> Step 3:
>> Edit your local hosts file in your system,below:
```
 192.168.1.37 python.org
 192.168.1.37 www.libsdl.org
 192.168.1.37 github.com
 192.168.1.37 pypi.python.org
```
PS: "37" is my pc's IP address,you can change them for yourself.

> Step 4:
>> Replace some keywords for your kivy's recipes on packages,it can be worked on my pc.
   Replace "https" with "http",if you found some rescipes cannot be download for you.
   eg: SDL SDL_image pygame. 
   If you want to download them,sometimes it is pretty slow.
