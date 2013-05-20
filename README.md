#backup
Backup is a simple tool to copy specific files and folders for subsequent backup. 
The files and directories handled by this are specified in a text file containing the
full path to each item as one line entry such as:
C:\code\projects.txt  
C:\Firefox Profiles\standard\*.*
D:\images\*.jpg

##Usage
usage: backup.py [-h] [--i [input_file]] [--o [output_dir]] [--p]

optional arguments:
  -h, --help        show this help message and exit
  --i [input_file]  text file containing items to back up, default is
                    'backup.txt'
  --o [output_dir]  output directory, default is \backup
  --p               precheck only, don't perform actual backup
 

##Dependencies


##Installation


##TODO


