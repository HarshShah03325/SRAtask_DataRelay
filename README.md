# SRAtask_DataRelay
Data Relay using MQTT protocol and multithreading 

Table of Contents

    About the Project
        Tech Stack
        File Structure
    Getting Started
        Prerequisites
        Installation
    Usage
    Results and Demo
    Future Work
    Troubleshooting
    Contributors
    Acknowledgements and Resources
    License


Aim and Description of project.
Refer this documentation
Tech Stack

This section should list the technologies you used for this project. Leave any add-ons/plugins for the prerequisite section. Here are a few examples.

Mosquitto c library
JSON-c
Multithreading 
Compression Algorithms

File Structure

.
├── code                    
│   ├── pub.c                             #publishing data using mosquitto lib
│   └── sub.c                              #subscribing to the data and storing it in 50 bots
                          
├── thread_1                    
│   ├── temperature.txt                   # 50 bots created using multithreading 
│   ├── humidity.txt         
│   ├── ph.txt         
│   └── air_pressure.txt                
├── thread_2
    ├── distance.txt                   
    ├── switch_state.txt
├── README.md 
             
Getting Started
Prerequisites

   

How to install them

   



Installation

   
