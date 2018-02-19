# merch
Root repo for merch

> From ACM Chair Jonathan Stark (Chair 1995-96):
>
> Caffeine originally went online in 1993.  The original was a 1970’s era Dr. Pepper machine that I purchased in Sterling 
> Illinois, and brought back to the University of Illinois in the back of a 1984 Jeep Cherokee.  It was originally owned by 
> a friend of an ACM member, Jeremy Johnson, whom I purchased it from.
>
> The original Caffeine ran on a Motorola 68HC11 micro-controller, which was the same processor used in the ACM Sign and the 
> PowerGlove Serial Interface, which were 2 of the most popular SigArch projects at the time.  It was maintained by me and 
> SigArch, through 1996 when I left the U of I.  Later groups sanded off the paint from the old pop machine and replaced the 
> HC11 with an intel processor.  The original HC11 version had a card swipe that used the “secret” social security numbers 
> that used to be magnetically encoded on the student ID’s to query the old “ph” (short for phonebook) campus directory to 
> look up members and log caffeine consumption to a web page.  You could also remotely drop cans of soda for friends at the 
> office through the web interface.
>
> The point of all this being that ACM@UIUC had a pop machine online well before 2001.  While CMU had a pop machine online 
> before Caffeine, Caffeine was one of the very first internet enabled pop machines.  :)
>
> It also, incidentally, served soda to Steve Wozniak at the very first Reflections|Projections in 1995.  CMU can’t say that :)

[![Join the chat at https://acm-uiuc.slack.com/messages/C6XD34KTM](https://img.shields.io/badge/slack-merch-724D71.svg)](https://acm-uiuc.slack.com/messages/C6XD34KTM)

## Overview 

[merch-hardware](https://github.com/acm-uiuc/merch-hardware)

[merch-embedded](https://github.com/acm-uiuc/merch-embedded)

[merch-ios](https://github.com/acm-uiuc/merch-ios)

[groot-merch-service](https://github.com/acm-uiuc/groot-merch-service)


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
https://www.google.com/patents/US8534494?dq=sensor+vending+machines&hl=en&sa=X&ved=0ahUKEwit3rDMyYvZAhUJqlkKHSVIDmQ4MhDoAQgtMAE
