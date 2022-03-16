The company you work for installs home management software and hardware. One full system contains:
    Thermostat panel.
    Security panel.
    Entertainment management.
    Cleaning robot: floors only.
    Lighting panel.

Your software supports homes across the province. Application servers are running php. Kingston houses one mysql database server with a mirror back server.

# Black/Grey/White box testing

## Black Box Examples:
1. To make sure the cleaning robot can clean the space properly, place some dirt(crumbs) in a corner to test if the cleaning robot can reach/clean corners or the room. 
2. To ensure the securiuty system is working properly, open a few windows/doors and see if the armed system alerts the homeowner.

## White Box Examples:

1. Testing the code that controls the cleaning robots to ensure that they can detect different surface materials. IE. values set in floor type variable changes when on different surfaces (hardwood, ceramic, carpet).

2. To test the security panel, you could test the code to ensure that only the proper credentials will allow access to it functions. IE. Testing with fake credentials, different combinations of numbers/characters.

## Grey Box Examples:

1. To test the lighting panel functionality, you could set the lights to "movie mode". Then turn the wifi/ disconnect the system from the network, and try to change the lighting mode.
     
2. To test the Thermostat panel, you could set the heat to on and at room temp (25C) then open the windows and see if the panel will activate the furance to try and ompensate for the loss of heat from the windows.


# Functional, Non  Functional and Volume Testing

## Functional Testing 
1. Thermostat - What is the max/min temp you can allow.
2. Lighting Panel - If you change the lights to mood lighting, do the lights dim 
3. Security System - Testing the system for minimum and maximum temperatures

## Non Functional Testing
1. Security System - Does the system alert the homeowner instantly after a detection or an hour later?
2. Thermostat - Testing the system for minimum and maximum temperatures?
3. Cleaning Robot - 

## Volume Testing 
1. Security Systems - Opening all the windows, doors and monitored access points at once. IE. How many requests can the system handle at one time? 
