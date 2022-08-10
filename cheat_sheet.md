
# Directory & File

> ### $ pwd
> 
> Check the full path of the current folder
>
> /Users/username

> ### $ ls
>
> A list of files and folders in the current directory
>
> ### $ ls -l
>
> A list of files and folders with details
>
> ### $ ls -a
>
> A list of files and folders including hiding files
>
> ### $ ls -al
>
> A list of files and folders including hiding files with details

> ### $ cd
>
> Go back to the root folder
>
> ### $ cd \<directory>
>
> Go to the specified directory
>
> ### $ cd `tab`
> 
> Press `tab` to choose a directory at the current level and get deeper
>
> ### $ cd ..
>
> Go back to one upper level directory

> ### $ mkdir \<directory>
>
> Create a folder in the current directory
> 

> ### $ touch \<directory>
> 
> Create a file in the current directory

> ### $ rm
>
> Delete a file or a folder
>
>> #### $ rm \<file>
>>
>> Delete a file
>>
>> #### $ rm -r \<directory>
>>
>> Delete a folder

> ### $ mv
>
> Move a file or a folder into another folder; Rename a file
> 
>> #### $ mv \<file> \<directory>
>>
>> Move \<file> to \<directory>
> 
>> #### $ mv \<directory> ..
>>
>> Move \<directory> to an upper level directory
> 
>> #### $ mv \<file_1> \<file_2>
>>
>> Rename \<file_1> into \<file_2>

> ### $ cp
> Copy a file or a folder to another folder
>> #### $ cp \<file> \<directory>
>> 
>> Copy \<file> to \<directory>
>>
>> #### $ cp -r \<directory_1> \<directory_2>
>> 
>> Copy \<directory_1> to \<directory_2>

> ### $ open
>
> Open a file or a folder
>
>> #### $ open \<file>
>>
>> #### $ open \<directory>

# Git

> ### $ git init
>
> Set up an empty Git repository in the current directory

> ### $ git status
>
> Check the status, what git looks like at the current stage

> ### $ git add \<file>
> 
> Snapshot the current change of the new or modified file
>
> ### $ git add .
> Add all the changes directly

> ### $ git commit -m \"\<commit>"
> 
> Commit the changes from the staging area (git add)

> ### $ git log
>
>  Check the commit message
>
>  Press ***q*** to quit the log

> ### $ git revert \<first7digits of the commit in the log>
>
> Undo a commit change

> ### $ git remote add origin \<SSH>
>
> Connect the local repository to Github

> ### $ git push origin main
> 
> Upload codes into a Github repository being created

> ### $ git clone \<SSH>
> Clone a repository

> ### $ git pull
> 
> Update the remote repository