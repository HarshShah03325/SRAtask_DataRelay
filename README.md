# SRAtask_DataRelay
Data Relay using MQTT protocol and multithreading 

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Problem Statement](#problem-statement)
  * [Tech Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
* [Installation](#installation)
* [Troubleshooting](#troubleshooting)
* [Future Work](#future-work)
* [Contributors](#contributors)
* [Acknowledgements and Resources](#acknowledgements-and-resources)

<!-- ABOUT THE PROJECT -->
## About The Project

### Problem Statement

```
Consider you have deployed various sensors in your office like temperature, pressure, gas, smoke, motion, proximity, etc. These sensors are present on different floors and rooms with 50 edge boards. You need to get the sensor readings to a single device like your mobile phone. Also, since sensors will be working the whole day, the size of data will increase tremendously. Considering that you need at least one week's data to provide the user with some statistics, you will have to compress and store the data on the user's device.
```
<p>
<a href="https://github.com/SRA-VJTI/practice-assignments/blob/master/Data-Relay/data-relay.md">Data Relay by SRA-VJTI</a>
</p>

### Tech Stack
Technologies used for the project.
* Mosquitto C Library
* JSON-c
* Multithreading  
* Compression Algorithm

### File Structure
    .
    ├── Code                 
    │   ├── sub.c
    |   |── compression_algorithm.c 
        └── pH.txt                       
    ├── thread_1                    
    │   ├── temperature.txt          
    │   ├── humidity.txt
    |   |── air_pressure.txt            
    │   └── pH.txt                
    ├── thread_2
    |   ├── distance_txt                   
    |   ├── switch_state.txt
    └── Readme.md
    
    
   
## Getting Started



### Installation
1. Open Terminal and follow commands
```sh
sudo apt-add-repository ppa:mosquitto-dev/mosquitto-ppa
sudo apt-get update
sudo apt-get install mosquitto
sudo apt-get install mosquitto-clients
sudo apt clean
```
2. Check Installation
```sh
netstat -at
```
1883 port should be established and running.


## Troubleshooting
* Common errors while configuring the project
> Errors tend to occur while library installation. Kindly download as per your system configurations.


## Future Work
- [x] Creating publisher and subscribers using MQTT protocol
- [x] Using multithreading to create various bots
- [x] Generating Random JSON
- [ ] Implementing Compression Algorithm
- [ ] Compiling all code

<!-- CONTRIBUTORS -->
## Contributors
* [Harsh Shah](https://github.com/HarshShah03325)

<!-- ACKNOWLEDGEMENTS AND REFERENCES -->
## Acknowledgements and Resources
* [SRA VJTI](http://sra.vjti.info/)
* [Shantanu Pande](https://github.com/shan515)
















    
                    
                    
