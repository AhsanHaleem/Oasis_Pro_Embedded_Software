# Oasis_Pro_Embedded_Software
An embedded software developed for a device called Oasis Pro using Agile and Object-oriented methodology.
* Software's programming language: C++ 
* Software's programming language framework: Qt framework  
* Tools used to make this software: Qt Creator IDE and Visual Studio

## Objective: 
The objective of this project is to demonstrate my abilities to work with four developers in a group of 4 implementing Object-oriented methodology and Agile methodology, which includes designing, developing, testing, deploying, and reviewing an embedded software for a device called Oasis Pro. Oasis Pro is a Cranial Electrical Stimulation (CES) device developed by Mind Alive Inc.

![image](https://user-images.githubusercontent.com/29932763/196058647-d4f84e0d-ebef-4a3f-82da-fd627852daf6.png)

## Decription of the embedded software

### Selectable Options on the device's screen
* Sessions
  * Session Groups
    * 30 Minute
    * 45 Minute
    * 3 hours
    * User Designated
  * Session Types
    * MES
    * Sub-delta
    * Delta
    * Theta
    * Alpha
    * SMR
    * Beta
    * 100hz
* Records
  * View Session History

### Interactable Elements
* Oasis Pro Device
  * Power Button
  * Up Button
  * Down Button
  * Confirm Button
* Admin Panel
  * Battery Combobox
  * Connection ComboBox

### Software Components Funtionality 
* Power Function
  * Need to hold the power button to turn on and off.
* Battery Display
  * According the built of the software, while the session is run, the device's display grapgh will show intensity levels and battery levels very 4 seconds. 
  * This means that if the user changes the intensity level while it's showing the battery, it will show the intensity level after 4 seconds. 
  * On the other hand, If it is already showing the intensity while and the user changed its intensity level, then the display will show the updated intensity level after one second.
* Recording
  * Recording is turned off by default. To record a session, the user needs to hold down the confirm button when he is ready to move on from the connection test.
* Record Viewing
  * The user can view any record through a user interface display that has been added to the display screen of the device above the power button.
* Menu
  * A menu has been displayed on the display screen of the device for the users to select different options and to view records.
* User Designated Sessions
  * A user can create and run user designated session through the device.
* Battery Replacement
  * The user can insert and replace the battery of the device and the software is abl to recognize that. 
  * If a battery is removed and then reinserted, the software is able to recognized that the user has replaced the battery and therefore the level will be reset to 100%.

### Team Members (name - github name)
* Ahsan Haleem - AhsanHaleem
* Ade Banjo - itsATB
* Alex Coyne - Sinash719 
* Zachary Neath - ZacharyNeath


