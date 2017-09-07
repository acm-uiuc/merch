# merch
Root repo for merch

[![Join the chat at https://acm-uiuc.slack.com/messages/C6XD34KTM](https://img.shields.io/badge/slack-merch-724D71.svg)](https://acm-uiuc.slack.com/messages/C6XD34KTM)

## Getting Started

Make sure you have Python and pip installed before starting 

There are a couple components of the Merch. To get all of them we use a tool called repo 

1. Install repo - https://android.googlesource.com/tools/repo/

    Mac OS
    ```sh
    brew install repo 
    ```

    Ubuntu 14.04+
    ```sh    
    sudo apt install repo

    ```
2. Make a directory to house your merch work
    ```sh
    mkdir merch
    ```
    
3. Within this directory run the following command to start managing the projects

    ```sh    
    repo init -u git@github.com:acm-uiuc/merch
    ```
    
4. Run the following command to grab the latest of all the repos 

    ```sh    
    repo sync
    ```
