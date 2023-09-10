# Linux
Learn to Cloud Day 1 
Standalone Videos Watched:
  - What is Linux: https://www.youtube.com/watch?v=PwugmcN1hf8 (not a fan of this video)
  - You NEED Linux for Cloud: https://www.youtube.com/watch?v=mxVq2DlPDWw&t=656s

Bash For Beginners Playlist: https://www.youtube.com/playlist?list=PLlrxD0HtieHh9ZhrnEbZKhzk0cetzuX7l
  [1 of 20]:  Welcome to Bash for Beginners
    - Introductory video. 
  [2 of 20]: What is the Difference Between a Terminal and a Shell?
    - Terminal: the environment in which you are issuing the Bash commands.
        - In the context of using Bash, a terminal is a text-based interface that allows users to input commands and receive text-based output from the operating system. It serves as a bridge between users and the underlying system, enabling tasks like running programs, managing files, and executing scripts through command-line instructions.
    - A terminal is a user interface that displays a command prompt, allowing users to input commands and see their output. A shell, like Bash, is the actual program that interprets these commands and communicates with the operating system to execute them. In essence, the terminal provides the interface, while the shell processes commands and manages system interactions.
  [3 of 20]: Setting up our Bash Environment
    - Fork Github Repo: https://github.com/microsoft/bash-for-beginners
    - Create a Codespace: VS Code in the cloud - you don't have to install anything locally. 
    - Terminal Commands:
      - ls -l: list all the directories that you have available to move into 
      - cd {insert directory name here}: change directory/enter a directory
      - ls: list all the contents in the directory you selected
      - code {insert file name here}: selects the file you will begin coding in
      - clear: clears all the output 



Learn to Cloud Day 2
Bash For Beginners Playlist: https://www.youtube.com/playlist?list=PLlrxD0HtieHh9ZhrnEbZKhzk0cetzuX7l
[4 of 20]: How to Get Help in Bash
  - Help Command: help - built-in command into Bash that allows you to get back information on other commands
    - Anything inside square brackets is optional
    - Anything that is divided by a vertial bar (pipe symbol | ) means that it is mutually exclusive
    - Use --help if you are already typing the command and don't want to clear the line
  - Man (Manual) Command: man - gives entire manual page for a given command
    - To get to the help of the manual, press H key
    - To move a half page down, press D key
    - To move up a half page, press U key
    - To move a full page, press space key
    - To move a single line down, press J key
    - To move a single line up, press K key
    - To quit help page, press Q key
    - To find examples, type "/EXAMPLES"
[5 of 20]: How to Navigate the Terminal with Bash
  - Print Out Working Directory Command: pwd
  - Change Working Directory: cd
  - Pushd and Popd ****
    - Further Explanation: https://opensource.com/article/19/8/navigating-bash-shell-pushd-popd
    - Further Explanation: https://linuxize.com/post/popd-and-pushd-commands-in-linux/

Learn to Cloud Day 3
Bash For Beginners Playlist: https://www.youtube.com/playlist?list=PLlrxD0HtieHh9ZhrnEbZKhzk0cetzuX7l
[6 of 20] How to List Content in the Terminal with Bash
  - ls: shows all the content in the current working directory
  - ls -a: shows hidden and unhidden files in the current working directory
  - ls S*: shows all the files and folder that begin with a capital S followed by any number of characters (can be used with any letters)
  - ls [CS]*: shows all files and folders that start with the a capital C or S followed by any number of characters
  - ls *md: shows all files that have the .md extension (can be used with any extension)
  - ls *.??: shows all files that have a 2 letter extension (each question mark represents one character)
  - ls [[:upper:]]*: shows all siles and folder that start with an uppercase letter
  - ls [[:lower:]]*: shows all siles and folder that start with an lowercase letter
[7 of 20] How to Find Files in the terminal with Bash
  - whereis: a command that locates the binary, source, and manual files for specific command name
  - whereis -b: just the binary of the results
  - which: returns the pathnames of the files which would be executed in the current environment
  - find: search for files in a directory heirerachy
    - find . -name "*.md" (the . represents the current director, -name means search by name)
    - find /home -iname files.txt (the -iname helps you search for files so it doesn't matter if it starts with an uppercase or lowercase letter)

Learn to Cloud Day 4
Bash For Beginners Playlist: https://www.youtube.com/playlist?list=PLlrxD0HtieHh9ZhrnEbZKhzk0cetzuX7l
[8 of 20] How to Work with Directories in the Terminal with Bash
  - mkdir: makes directories
  - mkdir -p: creates a subdirectory for a directory that does not exist yet
  - touch: makes files
  - mv: moving files
  - cp: copy files and directories and rename files in the copying process
  - rm: removes files
  - rmdir: remove directories
[9 of 20] How to View Contents in the Terminal with Bash
  - cat: shows the content of the file
  - head: shows first 10 lines of the content of a log file
    - use -n to state how many files you want
  - tail: shows last 10 lines of the content of a log file
  - more:  If the content of the file is too large to fit in one screen, it displays the contents page by page. You can scroll through the contents of the file by pressing ENTER or SPACE BAR keys.
      - defintion from https://ostechnix.com/the-difference-between-more-less-and-most-commands/
  - less: The 'less' command is also used to open a given file for interactive reading, allowing scrolling and search. If the content of the file is too large, it pages the output and so you can scroll page by page. It allows scrolling on both directions. Meaning - you can scroll up and down through a file.
      -defintion from https://ostechnix.com/the-difference-between-more-less-and-most-commands/
  - grep: The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression (grep stands for global search for regular expression and print out).
      - definition from https://www.geeksforgeeks.org/grep-command-in-unixlinux/
[10 of 20] What are Environment Variables?
  - Environment variables or ENVs basically define the behavior of the environment. They can affect the ongoing processes or programs executed in the environment.
  - env: presents all the enviroment variables that are currently available
  - echo: get the value of the environment variable
  - export: create environment variables (only available in curremt session)
      - you can make this more permanent by doing export in certain files

Learn to Cloud Day 5
Bash For Beginners Playlist: https://www.youtube.com/playlist?list=PLlrxD0HtieHh9ZhrnEbZKhzk0cetzuX7l
[11 of 20] How to Use Redirection and Pipelines in Bash
  - Everything that you see on the terminal either came from an output stream or an input stream.In Bash, you can redirect and or chain together that output using the redirection operator and the pipeline.
    

