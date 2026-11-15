## Task 2.1
Activity: Explore basic Terminal operations
|Operation / command name |What it does|What I observed|
|---|---|---|
|pwd|returns in which directory i am in |Directory Name|
|ls|returns all the files and folder names|Files and Folder in that Directory|
|ls -l|Displays files with permissions, owner, size and modification date|It showed detailed information about the files and folders|
|cd|Changes Directory|Changes from current directory to another another directory|
|mkdir|Creates a new directory|A new Directory is created|
|touch|Creates an empty file|A new empty file is created|
|cp|Copies file from location and pastes the file at given location|File is copy and pasted|
|mv|Rename or moves file|The File name is chnaged|
|cat|Shows the content in the file|Display file contents|

## Task2.2

1.The difference is that  overwriting removes the file's existing content and writes new content while appending adds new text to the end without deleting existing content.

2.Copying a file creates a duplicate of the original file so both files remain in their locations. Moving a file transfers it to another location so it is removed from its original location.

3.The current-directory display shows the full path of the folder I am currently working in. It helps me identify my location in the file system.

4.A directory-listing operation is useful because it shows all the files and folders in the current directory. It helps me find view and manage files easily.


## Task 2.3 – Understand Flags and Pipes

### Commands performed

| Command | Purpose | Observation |
|---|---|---|
| ls|Displays files and folders|Shows normal directory listing|
|ls -l|Displays detailed file information|Shows permissions, owner, size and date|
|ls -la| Displays detailed listing including hidden files| Hidden files starting with a dot are also visible|
|ls -lah|Displays detailed listing with human-readable sizes| File sizes are displayed in KB, MB or other readable units|
|ls -lah \| head| Displays only the first few lines of the listing. | Only the first 10 lines are displayed. |

### What is a pipe?

The pipe symbol (|) passes the output of one command as input to another command



## Task 2.4 – Understand Package Managers

I checked Homebrew, which is a package manager used in macOS.

### Commands performed

| Command | Purpose |
|---|---|
|brew --version| Checks the installed Homebrew version. |
|brew list|Displays the installed packages managed by Homebrew. |

### Why are package managers useful?

Package managers help users install, update and remove software easily. They also manage software dependencies and make it easier to maintain applications. Homebrew provides a convenient way to manage development tools and applications on macOS.

