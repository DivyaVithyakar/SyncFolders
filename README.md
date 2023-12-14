Folder Synchronization Tool
This Python script is a simple folder synchronization tool that periodically synchronizes two folders, maintaining an identical copy of the source folder at the replica folder. It logs file creation, copying, and removal operations to both a file and the console output.

Features
One-way synchronization: Ensures that the content of the replica folder exactly matches the source folder.
Periodic synchronization: The tool runs at regular intervals to keep the folders synchronized.
Logging: All file operations are logged to a specified log file and the console output.

Run the script with the following command:

python sync_folders.py /path/to/source/folder /path/to/replica/folder <interval> /path/to/logfile.txt
/path/to/source/folder: The path to the source folder you want to synchronize.
/path/to/replica/folder: The path to the replica folder where you want to maintain the copy.
<interval>: The synchronization interval in seconds.
/path/to/logfile.txt: The path to the log file where synchronization details will be recorded.

Error Handling
The script includes error handling to handle unexpected situations gracefully. If any errors occur during synchronization, they will be logged as error messages.
