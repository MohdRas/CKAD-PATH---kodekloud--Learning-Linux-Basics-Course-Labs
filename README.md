# CKAD-PATH---kodekloud--Learning-Linux-Basics-Course-Labs
CKAD PATH - kodekloud- Learning Linux Basics Course &amp; Labs


#SHELL 
- program that allows text-based-interaction between user & os.
- one of such shell is "bash shell"
- TYPE
    - linux shell - terminal
    - ubuntu desktop / graphical view
- HOME DIRECTORY
    - Different for each user - /home/rasid and /home/rehan.
    - other users cannot access the home directory.
    - home directory is represented by ~ (TILDE)
- COMMANDS & ARGUMENTS
    - echo Hello World - Here "echo" is command and "Hello World" is an argument.
    - uptime - Here "uptime" is command.
    - echo -n Hello World - Here "-n" is a "SWITCH / FLAG" - PRINITING WITHOUT TRAILING NEW LINE
- COMMANDS TYPES
     - internal / built-in - echo , cd, pwd
     - external - mv, date , uptime, cd
     - type "command" - it will tell us if a command is internal or external.
- basic linux commands
    - pwd -  present working directory pwd
    - pwd $home - print home directory
    - ls - list contents ls
    - mkdir - make new "list of directories" 
        - mkdir Asia Europe Africa America 
        - mkdir Asia/India/Mumbai 
        - mkdir -p Asia/India/Mumbai - "-p" make sure parent directory also got created.
    - cd - change directory cd dir1
        - cd .. -  one step back
        - cd  - back to home directory
        - cd /home/rasid - back to specific directory
        - absolute path
            - path from "root" to specific directory "Mumbai" 
            - pwd - /home/rasid/Asia
            - cd /home/rasid/Asia/India/Mumbai - "/" is the root directory. 
        - relative path
            - path from "current" directory to specific directory "Mumbai" 
            - pwd - /home/rasid/Asia
            - cd India/Mumbai - "/" is the root directory.
    - mv -  move file or directory
        - mv source-dir destination-dir
        - mv /home/rasid/Asia/India /home/rasid/America/NewYork - "India" directory will be moved inside "NewYork" directory
        - cp source-file destination-dir
        - cp /home/rasid/Asia/India/city.txt /home/rasid/America/NewYork - "city.txt" file will be moved inside "NewYork" directory
        - cp -r - "-r" for recursive operations.
    - rm - remove a file or a directory
        - rm /home/rasid/Asia/India
    - cat - to print file content
        - cat fileName - print
        - cat > fileName - open, edit & save ( control+d)
    - touch - create a new file
    

     
