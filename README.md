# Smart Elevator Control System ER Diagram

This repository contains the ER diagram for a smart elevator control platform designed for large commercial buildings, based on the project brief for **Smart Elevator Control** :contentReference[oaicite:0]{index=0}.

## 🖼️ ER Diagram Preview
![Smart Elevator ER Diagram](./Smart_Elevator_Control.png)

## Overview
The database models:
- multiple buildings
- floors inside each building
- elevators and elevator shafts
- floor requests
- ride assignments
- ride logs
- maintenance records

## Main Entities
- **Building**
- **Floor**
- **Elevator**
- **Elevator_Shaft**
- **Elevator_Floor**
- **Floor_Request**
- **Ride_Assignment**
- **Ride_Log**
- **Maintenance_Record**

## Design Notes
- Separates static configuration from dynamic ride data  
- Supports many-to-many (Elevator ↔ Floor)  
- Tracks full ride and maintenance history  

## Purpose
Designed for real-world high-rise infrastructure systems to manage elevator operations efficiently.
