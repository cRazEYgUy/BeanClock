# JellyLockClock8
An alternative to JellyLockClock7, for iOS 8.

#To-Do
- Make the tweak actually work. I decided to open-source this while working on it to allow others to see how it all works in the early stages. Also, I guarantee I'm going to need help with this :p
- Find a different name.
Here's acutal development stuff to sort out:
- Use a different method to hide the LS Clock, -[SBFLockScreenDateView _addLabels] sometimes doesn't hide the clock
- Change numbers into text i.e 7:30 changes to 'Seven|Thirty' or something similar. I presume one way of doing this is moving the numbers out of the 'currentTime' string and into their own using something like -[NSString range] and then converting numbers to text.
