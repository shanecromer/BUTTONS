
## BUTTONS
## CST205 FA21  12/08/2021
## Title: ## Final project team number 808##  Drum Machine ##
## Abstract: Trigger Drum Sound to make Beats.
## Authors: Shane Cromer scromer@csumb.edu###
## Yssa Traore <ystraore@csumb.edu>
## Tuan Nguyen <tunguyen@csumb.edu>
## Shane Cromer <scromer@csumb.edu>
## Ivan Martinez <ivmartinez@csumb.edu>

##  About this Project

   We created a vertical layout grid of qt buttons. We connected the button to click signals that trigger drum sounds.
   The original intention was to use trigger the drum sound with keyboard short-cut but we have not yet found how to connect the trigger event
   to keyboard keys.  We also attempted to use playsound to play the sound but were unable to make it function. We went with pygame mixer instead.
   We first kept the sounds in a separate folder but could not get them to play unless they were in the root folder.
   We added a slider that was intended for volume but have not been able to get the slider to work for volume.
   We attempted to replace the button with images button have not been able to do that. 
   
   As a future developed features

  1) We would like to store several libraries of drum sounds, have a drop down to select a drum kit and have
     the selected kit load to the buttons.  

  2) Ideally the sounds could be triggered with the keyboard.
 
  3) We would like to have an option for looping and recording sounds.

  4) A graphical readout of the sounds.
  
 
# Descriptions of important code blocks

# Sources cited QT Documentation

# https://github.com/shanecromer/BUTTONS


How to run program

The following packages are required to run the program.
from PyQt6 import QtCore, QtGui, QtWidgets
from PyQt6 import QtCore, QtGui, QtWidgets
from PySide6.QtWidgets import (QApplication, QLabel, QWidget, 
                                QPushButton, QVBoxLayout,QHBoxLayout)
from PySide6.QtCore import Slot

import pygame



