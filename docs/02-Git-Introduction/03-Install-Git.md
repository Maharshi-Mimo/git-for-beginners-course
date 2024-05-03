# Install Git
  - Take me to [Video Tutorial](https://kodekloud.com/topic/install-git/)
  
In this section, we will take a look at Installing Git

- Download the Git binaries for your specific machine
  ```
  https://git-scm.com/downloads
  ```
  - Installing git for Linux
    ```
    https://git-scm.com/download/linux
    ```
  - Installing git for Mac
    ```
    https://git-scm.com/download/mac
    ```
  - Installing git for windows
    ```
    https://git-scm.com/download/win
    ```
- Once, installed to check the version of the git run the below command
  ```
  $ git --version
  ```
- Once installation is complete, it is time to configure git so all commit have an author. 
  - To configure git run the below command to set author globally. 
    ```bash 
    $ git config --global user.name "Your Name"
    $ git config --global user.email "Your Email"
    ```
    OR
    ```bash
    $ git config --global --edit
    ```
    [Git global configuration](/images/Git_config_global.png)