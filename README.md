####Patch for installing ns2.35 on Mac os 10.9
It works well in Mac OSX 10.9. Before using this patch, make sure you have already installed other libraries like X11, xQuartz and so on. 

Tips: you can easily install these stuffs by homebrew or macports. 

Steps:

1. cd ns-allinone-2.35/
2. patch -p1 -i macos10.9.patch 
3. install

In addition, I also provide my install.sh, which appends several lines to environment variables.

Enjoy!

Contact me if you have any question csujedi at gmail.com
