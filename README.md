# Labmine-dev
Labmine is an electronic lab notebook for research and hobbies where process is the key.
<img width="1180" alt="vpd-image" src="front/doc/images/Curry_Process.png">

## Demo 
https://demo-labmine.c1.hacobuneapp.com/

## How to use
After preparing the environment to run docker, run the following.
```sh
# recursive cloning of the labmine-dev repository
git --recursive clone https://github.com/kumagallium/labmine-dev.git

# move to working directory
cd labmine-dev

# build on the local computer
docker-copose up --build
```
Go to "http://localhost:3000" in your browser and check that Labmine is running.
Please modify the environment variables as necessary.