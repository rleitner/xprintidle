# xprintidle #

xprintidle is a utility that queries the X server for the user's idle
time and prints it to stdout (in milliseconds).

## Building and Installing ##

Basically, type "meson build && ninja -C build install" to compile
and install the program.

### Dependencies ###

You need the development files for the X11, Xext and Xss library.

## Contributing ##

To contribute source code to xprintidle please use GitHubs Pull-Request feature.
Furthermore please make sure that you've run clang-format before commiting
changes.

To report a problem or request a feature please use GitHubs Issue-Tracker.
