# Intro to Linux
1. logging in
  - username and password
  - reset password
2. account basics
  - uid - user ID
  - gid - group id
  - file and folder permissions
    - read, write, execute
3. file structure
  - /etc
  - /home
  - /bin
  - /var
  - /usr
4. file commands
  - whoami - show user
  - ls - list files
  - chown / chmod - file and folder ownershi
    - r - read (not folders)
    - w - write
    - x - execute file / open folder
    - user:group - owner and group owner
  - mkdir - make directory
  - rm - remove file
  - rmdir - remove directory (must be empty)
    - rm -rf to remove full directory
  - cd - change directory
  - pwd - show current directory
  - getent
    - passwd - list user info
    - group - list group info
  - echo - write content to screen
    - echo "hello world"
  - variables - name-"name"
    - echo $name
      - echo "Hello $name"
     
