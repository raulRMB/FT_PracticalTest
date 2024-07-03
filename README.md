# Unreal Practical Test

## Objective
Create a game in which actors in the world will change their state when the player shoots a projectile through a hoop.

#### Unreal Version 5.3.2

### Logic Method
Use C++, Blueprints or a mix of both.  What ever you are most comfortable with.

### First Steps
Download the zipped starting project "FT_PracticalTest.zip" and read through the custom FT_PracticalTestHoop actor logic this should be the base for any custom hoops you create. 

## Implementation
Use as many actors as you need but you are required to create the following actors. You should be able to use as many of these actors in your scene without
much setup.

## Required Actors

### Broadcasters
These should inherit from the AFT_PracticalTestHoop class
#### Hoops
 - Blue: 1 point
 - Green: 2 points
 - Red: 3 points

### Listeners
These should inherit from the AActor class 
#### Score Text
An actor that renders text
 - Changes text to "Score; %Score%" when score increases
 - Changes text color to the last hoop that the projectile flew through

#### Hoop Lights
An actor that contains a light and a static mesh
 - Changes light color to the color of the last hoop that the projectile flew thought
 - Changes static mesh color to the color of the last hoop to increase score

#### Game Won Light
An Actor that has a light
 - Starts invisible
 - Only shows when the score is greater than 10

## Submit
A video recording demonstrating a working demo and a commentary of your implementation choices. Please zip the Unreal project. Provide links for both the video and the project.

## Example

https://github.com/raulRMB/FT_PracticalTest/assets/92171903/3ac43747-1b00-40d7-9cef-6b46e99145d8

