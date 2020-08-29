# Resources

## Robotics
1. [Robotics Knowledgebase](https://roboticsknowledgebase.com/)
2. [RL Sutton & Barto](http://www.incompleteideas.net/book/the-book-2nd.html)
3. [Programming for Robotics - ROS, ETH](https://rsl.ethz.ch/education-students/lectures/ros.html)
4. [How to Build a Mobile Robot Platform, Alexander Savinkin
](https://medium.com/geekforge-academy/how-to-build-a-mobile-robot-platform-2f838ffe84eb)
 
## Python
1. [Object-Oriented Programming in Python, Michael H. Goldwasser](https://cs.slu.edu/~goldwasser/oopp/download/oopp.pdf)  
   [Python to C++](https://cs.slu.edu/~chambers/spring19/datastructures/python2cpp.pdf)
2. [Placeholder]

## C++
1. [Python C++ compare](https://realpython.com/python-vs-cpp/)
2. [Competitive programming books](https://cses.fi/book/index.php)

## Linux
1. [Conda Docs](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html#managing-python)

## Command-line
### Books
1. [THE LINUX COMMAND LINE, WILLIAM SHOTTS](https://wiki.lib.sun.ac.za/images/c/ca/TLCL-13.07.pdf)
### File edit
1. Replace <old_string> to <new_string> in multiple files with <file_extension> in <file_directory>
```
find <file_directory> -name \*.<file_extension> -exec sed -i "s/<old_string>/<new_string>/g" {} \;
```
### Video
1. Render video
```
melt <input_final_name, e.g.corl2020_final.kdenlive> -consumer avformat:<output_file_name, e.g.output.mp4> vcodec=libx264 <bitrate, e.g.b=10000k>
```
2. Compress video
```
ffmpeg -i <input_file_name> -b <bitrate, e.g.300k> <outpu_file_name>
```
3. Show video streams
```
ffmpeg -i <file_name>
```
4. Copy selected streams 
```
Stream #0.0: Video: ...
Stream #0.1: Audio: ...
Stream #0.2: Audio
```
```
ffmpeg -i <file_name> -map 0:0 -map 0:2 -acodec copy -vcodec copy <new_file_name>
```



## Git
1. [Workflow](https://gist.github.com/blackfalcon/8428401)

## IDE
1. [Visual Studio Code Tips and Tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)




## Printer (Epson-XP3100)
1. [Tutorial Linux](https://tutorialforlinux.com/2019/09/25/driver-epson-xp-3100-ubuntu-18-04-how-to-download-install/3/)
1. [Epson Linux Driver](http://download.ebz.epson.net/dsc/search/01/search/searchModule)(epson-inkjet-printer-escpr_1.7.7-1lsb3.2_amd64.deb)

## Research Proposal
1. [Eidinburgh University](https://www.ed.ac.uk/files/imports/fileManager/HowToWriteProposal090415.pdf)
