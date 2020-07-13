# useful_macOS
Useful Commands for Mac OS (X).

## Multiple App Instances

Start another instance of an app, even if one is already running

`open -n -a APPLICATION-NAME`

> -n, --new Open a new instance of the application even if one is already running.
> -a, -- Opens with the specified application.

### Example

`open -n -a /Applications/Ableton\ Live\ 10\ Lite.app`


## List all network interfaces without `ifconfig`

`networksetup -listallhardwareports`
