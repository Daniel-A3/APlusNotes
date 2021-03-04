------------------------------------
# Comptia A+ Exam Notes
------------------------------------
## Topics Covered:

* Device Connections
* Email

------------------------------------
### Section 1 : Device Connections
------------------------------------


#### Tethering

 - Allows you to connect a phone to a device such as a laptop, and then use the internet/data connection from the phone
 on the device.
 - Some phones allow you to use hotspots, where a phone allows other devices to connect to its cellular data network.

#### NFC (Near Field Communication)
 
 - Allows you to send small amounts of data wirelessly over a limited area.
 - Could be used for payment and authentication systems.

#### Bluetooth 
 
 - Refered to as a PAN (Personal Area Network)
 - Connects our mobile devices, like smartwatches, phones and headphones.

#### IR connectivity (Infrared)

 - Included on many smarphones, tablets and watches.
 - Not really used for file transfers and printing anymore.
 - Now its mostly used for entertainment and remotes. (controlling volume, channel playing etc)

#### SD / Micro SD card

 - Many android devices allow you to increase your storage space by inserting an SD or Micro SD card.

#### Phone Updates
 
 - __PRL Updates__ : Preferred Roaming List, for CDMA networks(i.e., Verizon, Sprint), allows you to connect to the correct tower and can be updated Over The Air(OTA) - *in the background.*
 - __PRI Updates__ : Product Release Instructions, updates specific radio settings, ID numbers, network and country codes, can also be updated OTA.

#### IMEI and IMSI

 - __IMEI__ : International Mobile Station Equipment Identity, _identifies_ a physical device, every phone has a differnet IMEI and can be used to allow or disallow access, you can also use the IMEI to check if its locked or unlocked to a carrier.
 - __IMSI__ : International Mobile Subscriber Identity, _identifies_ the user, not the physical device, its usually stored on the SIM card, and allows the SIM to be swapped between phones, keeping the same IMSI and contacts and number etc.

#### VPN
 
 - Allows you to turn your phone into a VPN endpoint for secure communication.
 - Usually integrated into the phone OS, so no additional software needed, but configuration is usually needed.


------------------------------------
### Section 2 : Email on Devices
------------------------------------

#### Email Configurations

 - Retreiving Emails : POP3, IMAP
 - Sending Emails : SMTP
 - Corporate Emails : Microsoft Exchange
 - Intergrated Providers : ICloud, Google, Exchange Online, Yahoo

 - #### POP3 (Post Office Protocol 3):
 - Used for downloading mail to local mail client.
 - Downloads and optionally deletes from server.
 - Not used a lot anymore.
 - To connect to POP3 server, you need to provide the configuration information, this includes the name of the POP3 server, for authentication your username and password, you may also be required to provide a port number, this will be defined by your ISP but the default is tcp/110 for POP3, and tcp/995 for SSL(Secure Socket Layer) POP3.

 - #### IMAP (Internet Message Access Protocol 4):
 - Allows acces to mail on a central server.
 - The mail is usually stored on the server.
 - Configuration information is similar to POP3, but the default ports are: IMAP - tcp/143 or SSL IMAP - tcp/993.

 - #### SMTP (Simple Mail Transfer Protocol):
 - Send mail from a device to a mail server, or between mail servers.
 - Usually sent from a trusted device.
 - Authentication usually required.
 - Port numbers are different : SMTP(No Authentication) - tcp/25, SMTP(With Authentication) - tcp/587.

 - #### Microsoft Exchange:
 - Not used at home, but at an enterprise environment.
 - Has more features than just email : contacts, calenders, reminders.
 - Configuration Options : you usually need to provide - email, server, domain, username, password.
 - Intergrated message encryption with S/MIME, allows you to encrypt and digitally sign.

 - #### Commercial Email Providers:
 - Gmail - Google email, splits inbox into tabs, uses IMAP4 and POP3.
 - Yahoo - IMAP4 and POP3
 - ICloud Apple - IMAP4 and POP3