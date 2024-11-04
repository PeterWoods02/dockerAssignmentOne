## Docker Assignment - Agile Software Practice.

__Name:__ ....Peter Woods .....

__Demo:__ .... https://youtu.be/uGdSVPAW1PI ....

This repository contains the containerization of the multi-container application illustrated below.

![](./images/arch.png)

### Database Seeding.

I automated the seeding of my database by creating a seeding services which attached to my mongo database and got automatically stored in a seeding.json file as I launched a command on opening to automatically store the contents of the movies into the .json file.

### M.ulti-Stack.

I supported a production and development stack by creating a profile : dev, and adding mongo express and the seeding services into them. This allowed me to make two different run commands to launch which stack I needed. By adding --profile dev, into my command it launched the seeding and express too.