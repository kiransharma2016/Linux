## How to copy only file from current directory to some other directory 

find . -maxdepth 1 -type f   -exec cp {} ./temp/ \; 
