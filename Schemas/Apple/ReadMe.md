# Apple JSON Schemas
## CIS 2022 Security Benchmarks - Level 1 and Level 2
### For macOS Monterey

These JSON schemas were originally created with the goal of simplifying the enforcement of CIS benchmarks level 1 and level 2 for macOS Monterey and Big Sur.

These JSON schemas may cover additional settings that are not required by CIS benchmarks that are managed by the same preference domain for simplification during deployment.


#### Note: All of the .plists spit out by the [CIS-macOS-Security project](https://github.com/mvdbent/CIS-macOS-Security) level 1 and level 2 have been converted to JSON schemas. **HOWEVER com.apple.dock.plist is incomplete as it is missing the required keys to disable the usage of hot-corners to prevent screen saver activation or system sleep, in addition to some keys being un-tested in it's current version**. The other json schemas are functional from my testing, still need to add "more info" URLs for some and other housekeeping and basic cleanup on them. 

I'll continue working on updating these JSON schemas to add additional keys covered by the [Apple Device Managment documentation](https://developer.apple.com/documentation/devicemanagement) over the next few weeks to make them a bit more comprehensive in what they cover beyond just applying suggested CIS benchmarks to macOS Monterey (and macOS Big Sur in some cases).


### Navigation

- [Scripts and Things Homepage](https://gregknackstedt.com/)
- [Jamf Things - Home](https://gregknackstedt.com/Jamf_things/)
- [Scripts and Things Jamf JSON Schemas Home](https://gregknackstedt/scriptsandthings_Jamf_JSON_Schemas)
- [Jamf Things Documentation - Home](https://gregknackstedt.com/Jamf_things/Documentation/)
