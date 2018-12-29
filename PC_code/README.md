This Python code is run on PC.  
Required libraries are [pynput](https://www.baidu.com/link?url=Gou0RxE2Ek5mbO8HIIwFChPP0NydAUJT7AmOBAswV9kpkucx4TFM9q5H-A5M8crc&wd=&eqid=903db7c60003a8fc000000035c26cd06)
and [socket](https://docs.python.org/3.6/library/socket.html).  
Raspberry PI and PC should connect to the same network and configurate the IP addr in the code to that of the PI.  
For Mac system, you should set in the privacy and security to enable the terminal to get accesss to the keyboard.  

The control law now is simple:  
On press
w -> forward  
a -> left forward  
d -> right forward  
s -> backward

On release  
esc -> quit  
any of the 4 keys above -> stop  
