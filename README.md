# MorseCipher
Support Page for MorseCipher Application

## App Description 
MorseCipher is a Utility app that works completely offline. The app is designed to work on IPadOs and MacOS (via Mac Catalyst) for now.

The app has 2 Modes a user can select from, each having a different set of features, a Simple Mode and an Advanced Mode.

### Simple Mode
The app has the following features under the SImple Mode:
* Allows users to translate any alphanumeric text to and from Morsecode (International).
* Allows sharing Morse encoded messages either as a text via the iOS message app as an SMS or iMessage.
* Provides option to play and download the Morse encoded message as a standard Morsecode audio (short/long beeps).
* The Downloaded audio file can then be shared to another user for decoding in the app or using any online Morsecode audio decoding tools. 

### Advanced Mode
The app also has an advanced mode that provides the following features:
* Allows a pair of users to create a matching randomised cipher key secret, using a key exchange protocol.
* This cipher key then allows the pair of users to scramble/unscramble any body of text e.g. confidential information which they can share securely with one another.
* The app allows sharing the scrambled messages either using copy/paste commands or directly linking to the iOS message app to send the message as a standard SMS or iMessage to the recipients’ contact number.
* Provides option to play and download the Morsecode "encrypted" message as a standard Morsecode audio (short/long beeps).
* This Morsecode audio file is named morseoutput.wav, is downloaded and saved to the users Documents folder.
* The downloaded Morsecode audio file can then be shared to the other user that has the matching cipher key for unscrambling in the app. Note that the Morsecode audio file has to be manually transcribed by the recipient into Morsecode text format before using the app to translate. 

Lastly, note that to provide extra layers of security, once a message is scrambled, it can only be unscrambled in the app on the device of either one of the users that generated the cipher key used to scramble the original message, and only during an active key-exchange session. 
If the key-exchange session is terminated either by closing the app or clicking the reset button in the Cipher Keygen tab in advanced mode on both users devices, then the message can never be unscrambled, even using the app and the cipher key on another device, or using online Morsecode decoding tools.
This is done so as to provide a high-level of security for confidential information that is scrambled/unscrambled using the app.

## Privacy Policy
No user data is collected in this app.
This app is a Utility tool that works completely offline and does not connect to the internet.
It simply translates any message you type into a Morsecode format either using an extra layer of scrambling to "encrypt", "decrypt" or scramble the entered text. The app does not store the result of this processing anywhere. 
Please note that you are responsible for how you share any Morse-encoded or scrambled message you generate using this app to the recipient using available sharing tools on your Apple device such as copy/paste SMS or iMessage. 
So with this in mind, all necessary caution must be taken when using the app particularly for encoding/scrambling sensitive/confidential information and when sharing the result of this with the recipent.
