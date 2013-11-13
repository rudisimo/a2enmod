# a2enmod

a2enmod and its special invocations `a2enconf`, `a2ensite`, `a2dismod`, `a2dissite`
and `a2disconf` can be used to enable all types of Apache 2 configuration files.
When invoking these helpers in maintainer scripts, you should carefully check their
error return codes. These scripts must always be used with the -q (quiet) and -m
(maintainer mode) switches in maintainer scripts.

## Installation

### Installing with Homebrew (for OS X users)

Mac OS X users can install a2enmod with the [Homebrew](http://brew.sh)
package manager.

*This is the recommended method of installation if you installed a2enmod with
Homebrew.*

    brew install a2enmod

Or, if you would like to install the latest development release:

    brew install --HEAD a2enmod


### License

a2enmod is a brainchild of Stefan Fritsch <sf@debian.org> licensed under Apache
License 2.0.
