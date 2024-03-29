# Remove All Restrictions from School iPad
## Get the App Store back!

1. Settings -> General -> Reset -> Erase All Content and Settings. Follow the instructions. 
2. Wait for it to get to the Hello screen.
3. Set up the iPad as fast as humanly possible. 
4. Turn off WiFi as soon as you get to the home screen *through the Control Center by swiping down from the top-right corner of the screen*. The icon for WiFi in the Control Center should be *white*. By this point, you should still have the App Store.
5. Settings -> Wi-Fi -> the (i) next to your network (*be sure you are NOT connected to it*) -> Configure Proxy -> Automatic -> type "https://proxyblocker.github.io/proxy.pac" (without the quotes) -> Save
6. Turn back on WiFi in Control Center the same way you turned it off. The iPad will reconnect to your network. 
7. Enjoy! 

**IMPORTANT NOTE:** You must perform step 5 before connecting to *any other network*, otherwise you will go back to a normal school iPad within about three seconds. 

If you have any questions, DM [@schoolipadhelp](https://www.instagram.com/schoolipadhelp/) on Instagram. We'd be happy to help. 

Be sure to tell your friends!

## FAQ
#### How do I get Notability back? (districts that use Notability only)
You have two options: 
- Using a personal Apple ID, purchase it from the App Store for $12. This option is much less risky, but $12 is kind of expensive. 
- Briefly disable your protections to allow the MDM to push Notability to your iPad (extremely risky): 
  1. Connect to a network and wait about a day (shorter times may work; no guarantees). 
  2. Disable the proxy, but stay connected to WiFi. Make sure *not* to disconnect and reconnect. 
  3. Go to the home screen. Wait for Notability and other apps to start downloading, then turn off your WiFi the same way as you did the first time. 
  4. Turn back on the proxy. 
  5. Re-connect to your WiFi network. If all went well, Notability will finish downloading and installing and no other restrictions will appear. 

If you would prefer to not pay for Notability, we would recommend performing the second option immediately after setting up the iPad so that you don't lose too much work if something goes wrong. Also, you may not be able to update Notability if you do it the second way; the App Store will give you an error if you try. If you must update it, delete all MDM-provided apps and repeat the above process (although it's much more likely to fail the second time around). 

Getting Notability to push without restrictions is basically just luck. It seems to happen about a third of the time, so if you get a pile of restrictions, try again!

#### Can the school district just block resetting iPads?
Yes. We have a workaround.

#### Will I get in trouble for doing this?
Maybe? Hide your non-school-approved apps in the second page of a folder. You can always remove the proxy thing to let it turn back into a normal school iPad (but make sure to delete all your App Store apps first so that it won't get locked).

#### Can the school see from their end if you have done this?
It's possible. We're working on ways to make the school's MDM server think that the iPad has been registered without it actually having done so. 

#### Can I avoid having to type out the URL every time I connect to a new network?
If you have a Mac, try creating a configuration profile with Apple Configurator 2 that includes the proxy. However, this strategy appears to be temporary. For some reason, the iPad slowly reverts back to the school state if this is your only means of protection. Be sure to also manually add the proxy URL to each WiFi network. 

## FAQ for Teachers and Administrators
#### Students are goofing off in class a lot more now! How can we stop them?
You really can't. For your information, students have been messing around in class on their iPads for years without the App Store. Walking around the classroom, providing activities that require engagement, and creating more engaging lessons can help. Anyway, we've (almost) all got smartphones too. 

#### Can I do this with my iPad?
Sure, follow the instructions above. 

#### Is there anything that we can do to prevent this further?
Not by technical means. Blocking Erase All Content and Settings won't work (although we'll let you figure out why), requests to JAMF and Airwatch can be spoofed (even without a jailbreak), and restrictions cannot be applied before activation. 

#### Whodunnit?
A talented group of seniors at a public high school in upstate New York came up with the general process. It was shared through a Discord server (alledgedly) to members of a group in California, who posted it on Instagram. This site is a modified version of that Instagram post, tested and confirmed to work on another district's iPads. 



`Copyright 2019 InVEXers@mtka and The Underground Helpdesk. All rights reserved.`
