# launchpad-release
This is a helper script I use on my Ubuntu VM to release pam\_panic from github.
You need to have one previous release to use it, where it will get the debian directory from.

You need to set the `SOURCE` and `PPA` variable.

After that you just run `./launchpad-release [ VERSION NUMBER YOU HAVE TAGGED, RELEASED AND SIGNED ]`.
