#Add key to Info.plist for request permission to to User’s location`

In order to use the user’s location you need to request permission from the user by adding the keys “NSLocationWhenInUseUsageDescription” or “NSLocationAlwaysUsageDescription” to your Info.plist file, with the value blank or optionally a message included in the prompt to the user. One of those two key is required in iOS 8 to ask for your location.
