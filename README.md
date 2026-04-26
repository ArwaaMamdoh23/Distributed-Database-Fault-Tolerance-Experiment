# MongoDB Replica Set Failover Simulation

## Overview
This project demonstrates MongoDB replica set behavior, including failover, primary election, and replica set reconfiguration. It simulates how distributed databases maintain availability and consistency during node failures.

## Features
- Force primary step-down to simulate failure
- Trigger automatic election in replica set
- Reconfigure replica set member priorities
- Observe cluster state transitions
- Monitor replica set status

## Requirements
- MongoDB running in replica set mode
- Python 3.x
- PyMongo library

## How It Works
1. Connect to MongoDB admin database  
2. Force primary node to step down  
3. Wait for automatic election process  
4. Reconfigure replica set priorities  
5. Inspect final cluster state  

## Technologies Used
- Python
- MongoDB
- PyMongo

## Usage
python main.py

## Learning Outcomes
- Replica set architecture
- Leader election in distributed systems
- Fault tolerance in databases
- MongoDB administration commands

## Important Notes
This script must be run in a properly configured MongoDB replica set environment.
