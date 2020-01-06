# xmgrace-4k
This is a copy of xmgrace and the font is enlarged to be clearly seen on 4k monitor.
The original xmgrace doesn't support high dpi so the font becomes too tiny to see on a 4k monitor. So I modifed the font size from the source file. You need to recompile it.
I recommend you to install grace by the command(ubuntu)
```
sudo apt-get install grace
```
So that all the required libraries would be installed automatically by the system. And then recompile it.
```
git clone git@github.com:r-hou/xmgrace-4k.git
cd xmgrace-4k
./configure
make 
make install # or sudo make install
```
If you have any further question, please refer to [this link](http://plasma-gate.weizmann.ac.il/Grace/doc/UsersGuide.html#ss2.1).