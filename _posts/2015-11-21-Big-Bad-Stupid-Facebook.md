---
layout: post
title: Big Bad Stupid Facebook
---

If the Facebook knows your mobile number, know that regardless of your privacy setting it's accessible to virtually anyone.

To check this vulnerability for yourself go to [Facebook account recovery page](https://www.facebook.com/login/identify) and try entering some of your friends' mobile numbers in username field. If they had entered their number to the Facebook, you'll get a response with your friend's profile picture and name. And this process can be easily automated using commonly available tools. As for the safety mechanisms, the only one seem to be implemented is IP address blacklisting after about 100-150 tries. This can also be easily bypassed by using a botnet or if your ISP provides dynamic IP addresses, by simply disconnecting and reconnecting to the network. I was able to write a script which check 10,000 numbers well within an hour.

Within the 10,000 numbers I checked, I found about 1,200 numbers are already entered in Facebook.(I checked all the numbers in a random 10,000 range) So it's just a matter of days to collect the mobile numbers of all users of a given network.

Apparently this is a feature(not a bug) of Facebook which suppose to help the users to recover there user accounts. But because of the poorly implemented safety mechanisms an attacker can easily abuse this feature to map mobile numbers with user profiles and do a target attack on a specific person. For example this could easily pave the path for a successful Voice phishing attack - more effective because the computer user is not aware of the fact that his phone number may have ended up in the wrong hands. Just imagine that the crooks call your mobile and address you by your full name and back up their statements with information about you taken straight from your [Facebook] profile.
