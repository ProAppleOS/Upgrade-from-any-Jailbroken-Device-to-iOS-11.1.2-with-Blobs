- Copyright by ProAppleOS © ;
- MADE BY @ProAppleOS on Twitter; 
- ANY QUESTION? -> @ProAppleOS on Twitter 

# Upgrade from any Jailbroken Device to iOS 11.1.2 with Blobs

How to Upgrade any Jailbroken Device to iOS 11.1.2 with Blobs

DOING THIS IS AT YOUR OWN RISK! I'M NOT RESPONSIBLE FOR ANYTHING.

```Requirements:```
- a Mac (or virtual Machine) on macOS 10.12.6 (I know a futurerestore windows version came out, but idk how to use it)
- a Jailbroken Device
- SHSH Blobs for iOS 11.1.2 


                                  Currently Supported Devices for UPGRADING
- ALL JAILBROKEN DEVICES THAT SUPPORTS THE TWEAK ```NonceSet```


                                                 DOWNLOADS:

- Download iPSW for your Device! You need ```iOS 11.1.2 IPSW``` You can Download iPSW here: www.ipsw.me 
- Download THIS fork from futurerestore (https://goo.gl/Y4qfai)
- (Optional: download Reiboot https://goo.gl/orQLhk)

                                                 Lets Go :)
                                     
                                     
1. Create a folder on Desktop and name it ```Upgrade```
2. Put the iOS 11.1.2 IPSW you downloaded at the beginning into the ```Upgrade``` folder.
3. Open ```futurerestore_macos``` folder and put the file ```futurerestore_macos``` into the ```Upgrade``` folder.
4. Copy your SHSH2 blob from iOS 11.1.2 and put into ```Upgrade``` folder.
5. Rename your Blob name to ```blob.plist```        NOT ```blob.shsh2.plist```!
6. A popup will appear so click ```use .plist``` and click ```enter```
7. Open your SHSH Blob.
8. Scroll to the very bottom and you'll see a long string of characters that is SIMILAR to ```0x28tf5c185sj9```, but NOT IDENTICAL

9.  Add this Cydia repo on your device (http://julioverne.github.io/)
10. Search for ```NonceSet```
11. Download and install
12. Open ```NonceSet``` app  example here (https://goo.gl/KBmt7Z)
13. After you opened ```NonceSet``` it should look like this (https://goo.gl/no5mhb)
14. Now put the ```long String (Nonce)``` you found inside the Blob on the Mac before in the ```boot-nonce:``` section
15. Click ```return``` on iPhone keyboard and you should see this (https://goo.gl/t6rs8Gxz)
- ```Nonce (xxxxxxxxxxx) has been sucessfully set.```
    The xxxx is the nonce you found in the blob
        
16. Download & install ```MTerminal``` in Cydia
17. Open ```MTerminal``` app on the Homescreen
18. Type ```nvram auto-boot=false```
19. Type ```Reboot```
20. Now it should restart and go into ```Recovery Mode```
- NOTE: ↓ YOU CAN´T GO INTO NORMAL MODE BY REBOOTING, UNLESS YOU DO THIS ↓ !
- If you decided enter Normal Mode you need to use ```Reiboot``` download, install & open it, then click on ```Exit Recovery Mode```
21. If you want to go further ↓


                                        Now go back to your Mac!
 
1. Close the your SHSH Blob file (don´t change anything inside the blob file)
2. Rename your blob to ```blob.shsh2``` NOT ```blob.shsh2.plist``` or NOT ```blob.plist.shsh2```
3. A popup will appear, click ```use .shsh2```

Now you are all set for your Upgrade! Now you should have this in the ```Upgrade``` folder on Desktop:
- blob.shsh2
- futurerestore_macos
- iOS 11.1.2 IPSW


                        NOW THE UPGRADE PROCESS! Be patient! Don´t type anything wrong!
                              
                              
1. Open Terminal
3. write ```cd (drag your Downgrade folder into Terminal)``` and enter
3. type ```ls``` and enter
4. now you should see all the files in your ```Upgrade``` folder
5. drag ```futurerstore_macos``` file into terminal and click enter (you should see lots of commands)
6. write this
- ```./futurerestore_macos -t (drag blob) --latest-sep --latest-baseband (drag iphone11.1.2.ipsw)``` 
- Good example here: https://imgur.com/a/02EnO
7. Plug your Device in
8. Unlock your Device
9. CROSS FINGERS AND click Enter in Terminal
- ITS NORMAL THAT YOUR SCREEN OF DEVICE TURNS INTO GREEN (JUST IN THE UPGRADE PROCESS)!
10. Now it should work 
11. Wait about 5-10 Minutes
12. Your Phone restarts now.
13. Set up your Device
14. Install a Jailbreak if one is out :)

                                         DONE! ENJOY YOUR JAILBREAK :D
- Feel free to Donate :) https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AXEXQHKE2GHNC


                                             
- THANKS TO @tihmstar for futurerestore
- THANKS TO @siguza for v0rtex Exploit
- THANKS TO @Julioverne for NonceSet
- THANKS TO @firstencounter for the futurerestore fork that works with iOS 11
                                             
                                       MADE BY @ProAppleOS on Twitter 
