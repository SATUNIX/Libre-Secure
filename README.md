# Libre-Secure
Libre Secure is a software suite designed to keep watch over your local wireless landscape. 

Imagine a surveillance camera for the electromagnetic spectrum. Libre Secure combines traditional data harvesting and smart data analytics to provide you with sorted device in the area.   

## How does this help me?
Imageine if your home got broken into? Thieves wearing masks, shoplifters looting your store? 
Now you know the what, where, and who was in the area.
Combined with smart data analytics you can filter to novel devices for a specific time. 

## Scenario summary: 
- You got robbed at 1AM? Don't recognise the person/s?
- Access the device running Libre Secure, filter out found devices for that time period that the device has not seen before / novel devices.
- Provide device MAC addresses to local authorities for further investigation.

## How it works:
Inspired by Kismet and other OSINT tech, data harvesting, and SIEM data analytics.
Libre secure provides a log of who was in the area, when, and how many times that device has been seen before. 
Providing you with a extra way to track, log, and hunt malicious actors. 

## Developers:
**Feasibility Overview:**

Wi-Fi Probe Requests: Devices looking for Wi-Fi networks send probe requests that can be captured. These requests typically include the MAC address of the device and the SSID of the network it's seeking.
Wigle Integration: Wigle's database maps Wi-Fi networks to geographic locations. By querying this database with SSIDs from probe requests, you can potentially find the approximate location of these Wi-Fi networks.
Google Maps API: The Google Maps API can translate GPS coordinates into street addresses and provide access to Street View images.

Kismet-like tools can capture device bluetooth and wifi mac addresses (only working if randomisation is off) 

## Installation:
Do later after planning hardware build 
