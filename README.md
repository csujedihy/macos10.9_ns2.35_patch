####Patch for installing ns2.35 on Mac os 10.9
It works well in Mac OSX 10.9. Before using this patch, make sure you have already installed other libraries like X11, xQuartz and so on. 

Tips: you can easily install these stuffs by homebrew or macports. 

Steps:

```
$  cd ns-allinone-2.35/
$  patch -p1 -i macos10.9.patch 
$  ./install
```
In addition, I also provide my install.sh, which appends several lines to environment variables.

Enjoy!

Reference 
1. [Debugging ns-2 in Xcode (in Chinese)](http://blog.jeswang.org/blog/2014/07/07/debug-ns2-with-xcode/)

Contact me if you have any question csujedi at icloud.com
