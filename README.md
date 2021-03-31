# ChordRecogniser
A simple plugin that attempts to determine what chord a set of midi notes represents. Built using [iPlug2](https://github.com/iPlug2/iPlug2).
## Build Instructions
### XCode (macos only)
Open `ChordRecogniser.xcworkspace` in `Examples/ChordRecogniser/` using XCode, and use Build (cmd+b). 
### Other IDEs
Untested. Following the build instructions in the examples in the [iPlug2](https://github.com/iPlug2/iPlug2) repository should work.
## Usage Instructions
[Reaper](https://www.reaper.fm) is the suggested DAW to use this plugin in. On a new track, first add my ChordRecogniser plugin to the fx chain, then add your plugin that generates audio (from midi input). My plugin should not eat up the midi input that should be sent to your plugin. Other DAWs should have similar ways of chaining together plugins, but Reaper was the only DAW I used to test my plugin.