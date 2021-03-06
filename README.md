[Lights Out](http://samturner.github.io/lights-out/)
========================

[Lights Out](http://samturner.github.io/lights-out/) is a Preference Pane that automatically changes the OS X Yosemite to dark theme at night and light theme during the day.

![Lights Out Screenshot](http://i.imgur.com/8cgnrGQ.png)

### Features
- Enter the time of day you want the dark theme to turn on and turn off.
- Lives in a simple PrefPane that doesn't clutter your menu bar or dock.
- Efficient process to check the time and update. Uses less than 0.1% CPU and has no impact on battery life.

### Coming Soon...
- Use your location to determine sunrise and sunset times and use these to change the theme.
- Add a launchd service to make sure this runs at start up.
- Rewrite the daemon structure so as to fix a number of bugs.

If you want to keep up to date I'll post about the project regularly on Twitter - [@rheotron](http://twitter.com/rheotron). Also thanks to [iccir](https://github.com/iccir) for his help identifying the API Apple uses to do this and making a bunch of helpful contributions.

## Contributing

If you'd like to help out, clone the repository, make some changes and issue a pull request. If you come across any bugs or think of any features you would like, please create an issue and I'll look into it ASAP.

There are two seperate project files: one for the actual PrefPane and one for the daemon that runs in the background to control the change of theme.

## License

Copyright (c) 2014 Sam Turner

Licensed under the [GPL License](http://choosealicense.com/licenses/gpl-2.0/).
