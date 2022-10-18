# Oasis_Pro_Embedded_Software
An embedded software developed for a device called Oasis Pro using Agile and Object-oriented methodology.

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
o	We decided that there would be a menu to choose between operating the device and viewing records. This is done after the device turns on and appears in the display above the power button.
•	User Designated Sessions
o	Based on the specifications we made it possible to potentially add a user designated session through the device, and we also made it possible to run user designated sessions. Because on the real device, user designated sessions are added via the David Session Editor so we decided to replicate that by having the ability to add user designated sessions through the device and database but not through the UI. So to be clear, you can't add a user session through the GUI and that's on purpose.
•	Battery Replacement
o	If a battery is removed and then reinserted and the battery level is critical or lower we will assume that you replaced the battery and therefore the level will be reset to 100%. This is to replicate the fact that the device uses 9V disposable batteries.
•	Mediator
o	We decided to use the mediator design patter to properly encapsulate the forward facing functionality of the UI and the back end business logic of the device. This makes it so that all important things are calculated and monitored by the device and the MainWindow updates the UI and tells the Device what it needs and what it's supposed to do.


### Team Members
* Ahsan Haleem
* Ade Banjo
* Alex Coyne
* Zachary Neath


