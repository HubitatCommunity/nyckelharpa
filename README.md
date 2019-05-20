# Nyckelharpa
![image](https://github.com/arnbme/nyckelharpa/blob/master/images/nyckelharpa.jpg)  
**The buttons and levers controlling Hubitat Elevation's Home Security Monitor's strings.** 
## Purpose
Nyckepharpa is a user created Hubitat Home Security Monitor (HSM) extension, providing features not available in HSM. Additionally, it simplifies setting up security related messaging. 

## Features

* Under user control, forces HSM arming when a contact is open.<br /> 
*Why is this needed?*  HSM does not arm the system when a contact is open. Examples:<br />
It's 1AM, you want to arm the system for the night, but a contact is broken.<br /> 
You are away from home, forgot to arm the system, and when you try, oops the back door is open. 
* Adjusts Hubitat's mode when HSM's arm state changes. (HSM adjusts HSM's arm state when the Hubitat mode changes)
* Provides an easy to use, security related message control center with output to TTS, Speakers, and Pushover

* Keypads: Centralite V2 and V3, Iris V2, and UEI (beta) devices may use a ported version of Mitch Pond's Keypad DH, making the keypad function as it did in SmartThings with the [SHM Delay SmartApp](https://community.smartthings.com/t/release-shm-delay-version-2-0/121800). It uses a ported to HE version of the SHM Delay User Pin maintenance module allowing for a "Panic Pin", with optional restrictions by use count, time. and keypad device. 

* When the Panic key is pressed or a Panic Pin is entered using the ported version of Mitch Pond's keypad with the Nyckelharpa app, and a properly configured HSM Custom rule is active:
The system immediately executes the custom rule's alert functions

## Source Code and Documentation
https://github.com/arnbme/nyckelharpa
