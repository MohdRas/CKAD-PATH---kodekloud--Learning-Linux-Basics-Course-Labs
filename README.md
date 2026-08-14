# CKAD-PATH---kodekloud--Learning-Linux-Basics-Course-Labs
CKAD PATH - kodekloud- Learning Linux Basics Course &amp; Labs


#SHELL 
- program that allows text-based-interaction between user & os.
- one of such shell is "bash shell"
- TYPE
    - linux shell - terminal
    - ubuntu desktop / graphical view
- HOME directory
    - Different for each user
    - other users cannot access the HOME directory.
    - HOME directory is represented by ~ (TILDE)
    - echo $HOME 
            - print HOME directory on CMD 
            - mohdrasid@mohd-rasid01:~$ -> TIDLE (~) means HOME directory 
            - If "/" is in-place of "~" then it is a ROOT directory
    - cd
            - **It will directly move to HOME directory.**
            - If nothing specified after "cd" command then it will automatically go to HOME directory.
            - 
- COMMANDS & ARGUMENTS
    - echo Hello World - Here "echo" is command and "Hello World" is an argument.
    - uptime - Here "uptime" is command.
    - echo -n Hello World - Here "-n" is a "SWITCH / FLAG" - printing without new line.
- COMMANDS TYPES
     - internal / built-in - echo , cd, pwd
     - external - mv, date , uptime, cd
     - type "command" - it will tell us if a command is internal or external.
- BASIC LINUX COMMANDS
    - pwd -  present working directory
    - ls - list contents ls
    - mkdir - make new "list of directories" 
        - mkdir Asia Europe Africa America 
        - cd Asia
        - mkdir India/Mumbai - It will try to create "Mumbai" inside "India". Because "India" does not exist so it failed.
        - mkdir -p India/Mumbai - "-p" make sure parent directory also got created.
    - cd - change directory cd dir1
        - cd .. -  one step back
        - cd  - back to HOME directory
        - cd /HOME/rasid - back to specific directory
        - absolute path
            - path from "root" to specific directory "Mumbai" 
            - pwd - /HOME/rasid/Asia
            - cd /HOME/rasid/Asia/India/Mumbai - "/" is the root directory. 
        - relative path
            - path from "current" directory to specific directory "Mumbai" 
            - pwd - /HOME/rasid/Asia
            - cd India/Mumbai - "/" is the root directory.
    - mv -  move file or directory
        - mv source-dir destination-dir
        - mv /HOME/rasid/Asia/India /HOME/rasid/America/NewYork - "India" directory will be moved inside "NewYork" directory
        - cp source-file destination-dir
        - cp /HOME/rasid/Asia/India/city.txt /HOME/rasid/America/NewYork - "city.txt" file will be moved inside "NewYork" directory
        - cp -r - "-r" for recursive operations.
    - rm - remove a file or a directory
        - rm /HOME/rasid/Asia/India
    - cat - to print file content
        - cat fileName - print
        - cat > fileName - open, edit & save ( control+d)
    - touch - create a new file
    

     
