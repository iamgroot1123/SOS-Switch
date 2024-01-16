The main objective of this project is to create an SOS switch. This system is designed to send emergency messages and make calls when the user is in a dangerous situation or requires assistance. It can be integrated into various devices, including smartphones, wearable gadgets, vehicles, and home appliances.

- It sets up the system to communicate with a GSM module.
- It configures the system to go into sleep mode to save power when not in use.
- It reads the state of an SOS button. If the button is pressed for 5 seconds, the system wakes up from sleep mode, gets the current GPS location, and sends an SMS with a Google Maps link of the location to a predefined phone number.
- It also listens for incoming calls. If a call is received, it wakes up from sleep mode and answers the call.
- After the call ends, it goes back to sleep mode.

This kind of system can be especially used by children who are outside or at home alone. It provides a quick and discreet way to inform about their whereabouts for help.
