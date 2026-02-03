# Asset Inventory and Risk Classification 

## Overview
This project documents a basic asset inventory and sensitivity classification for a small network environment. The goal was to identify connected assets, review how they are accessed, and think through potential security risks related to confidentiality, integrity, and availability (CIA triad). 

Asset inventories are an important starting point in cybersecurity because it is difficult to protect systems without knowing what assets exist and how they are used.

## Scope 
The assessment focuses on a small home network that can also represent a remote work or small business environment. Only network connected devices within this environment were considered. 

## Approach 
For this project, I:
- Identified key network connected devices 
- Recorded basic details such as ownership, network access, and physical location 
- Noted how each device connects to the network and what type of information it may contain 
- Classified assets by sensitivity based on the potential impact if they were compromised 

## Asset Inventory 
The asset inventory is documents in ![asset_inventory.md](asset_inventory.md).
Each asset includes: 
- Network access frequency 
- Owner responsibility 
- Physical location 
- Sensitivity level 
- Brief security notes 

## Observations 
- Devices that are always connected to the network may present higher risk 
- Personally owned devices often store more sensitive information 
- Guest and smart devices increase the overall attack surface 
- Central devices such as routers are critical to network security 

## Context 
This project was completed as part of the Google Cybersecurity Certificate (Course 5: Assets, Threats, and Vulnerabilities)