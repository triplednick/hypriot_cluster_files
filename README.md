# Overview

This repo holds the files needed to flash the raspberry pi 3's I am using for my Kubernetes cluster. 


# Files

### config.txt 
The config.txt files holds a configuration that will allow the Raspberry pi's wifi to work out of the box. 

### user-data.yaml 
The user-data.yaml files holds information about the OS being flashed including the wifi credenetials, host name, and user information.

### run.sh
The run.sh script uses the "flash" cli to use the config.txt and user-data.yaml file to flash an sd card appropriately.
