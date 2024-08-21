These debloater files were designed for a Samsung phone, but would work on any Android phone. I could only test it on my own (Samsung S20 FE).
\
\
To use it you have to download the android sdk tools and unzip the folder somewhere. Put the executable from the following repo into the same folder (universal android debloater - https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation). Turn on the USB debugging in your phone in the developer options and open the executable downloaded. Accept the debugging request on your phone (if not there try turning debugging off and on and start the executable again). When it finally works, go to the settings and under the Backup separation in the UI press "Open backup directory". This opens the directory where the file from this repo has to be inserted. After done, restart the UAD and go to settings again. Choose the filename of the file you inserted in the dropdown menu under the Backup separation in the UI and press "Restore". This should disable/delete every package that I exported to delete/disable.
Try them out, see what works for you, maybe take the time to look up whats gonna be uninstalled and choose what suits you most.
\
\
With standard you will barely have any bloatware apps in your menu. This type of selection is for debloating the phone by a bit. Reducing telemetry, but still having a very stable device with all possible features. All functions are still available, but most bloatware apps and packages will be deleted.
\
\
"Minimal Recommended" aims to debloat the phone even more. Its there to remove all apps that Google, Microsoft, Samsung and Facebook and etc. forces on you. You might need an external device, to load apks on your phone, or install apps before debloating. This removes Samsung DEX, keeps SmartView (just in case), and removes many Knox features like Secure Folder (which is deprecated anyway, Android uses now Work profiles). It also takes a more radical approach removing the clock app, which means youd need to use an alternative. It still runs stable, as the necessary and "unnecessary" features are still available.
\
"Minimal Extended" is just as the previous package version, but with more packages removed. Many unnecessary apps will be gone, some functions might not work but the most necessary functions will work. This includes the packages for all browsers (install your own via an apk from USB). Samsung Location packages for example will be deleted, and therefore Samsung apps like Samsung health and camera would have a problem with it (camera wouldnt be able to put the location in each photo. Major security improvement). 
\
\
"Custom" is a version that I personally use. I wanted to minimise everything, but still retain the functions that I need everyday. If you want you might wanna try it. I dont need Accessibility, Samsung DEX, weather, samsung pay... And more. I download dialer, calculater, contacts, browsers, etc. that are open source. I still kept some Samsung apps.
