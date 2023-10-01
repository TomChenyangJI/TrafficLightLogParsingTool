This is a tool designed to parse the specific log files, with different types of data in separate log files. One type of file records the data of traffic lights collecting by many different instruments, including radar, lidar, camera, etc. And another type of log files records the data of some features of the traffic lights, including the id, height, GPS coordinates, etc. 

The function of this tool is to find out the traffic light position, and then match its own features which are stored in another log file. This tool is programmed in Python, and compiled to exe format with Pyinstaller package. 

You need to add the log file path to the file file_source.txt, which lies in the same directory as implementation.exe. The steps of making use of this tool are ,firstly, to add the path to the log files/directories/rar packages holding the log files to the file_source.txt, then to double click the file implementation.exe. 

The result will be save to a new file called result{hour}_{minute}_{second}.txt. Here, the "hour", "minute", "second" are the moment when the execution happens. After the execution of the implementation.exe. Each execution will create a new result file. 
