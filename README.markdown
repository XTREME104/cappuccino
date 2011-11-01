Welcome to Cappuccino for Adobe Air and Flash!
======================

To find the original version of Cappuccino, made for web applications, go to <http://github.com/cappuccino/cappuccino/issues>

This version of Cappuccino is made for ActionScript, rather than JavaScript, so it is made to create Adobe AIR, and Flash applications, rather than web applications.

Introduction
------------
Cappuccino is an open source framework that makes it easy to build desktop-caliber applications, that run in a web browser.

This modified version of Cappuccino is built on top of technologies like ActionScript, and it implements most of the familiar APIs from GNUstep and Apple's Cocoa frameworks. When you program in Cappuccino, you don't need to concern yourself with the complexities of technologies like MXML, or CSS. The unpleasantries of building complex applications are abstracted away for you.

For more information, see <http://cappuccino.org>.

System Requirements
-------------------
To run ActionScript Cappuccino applications, all you need is Adobe AIR, or Flash (Depending on which the application was made for). Flash is already installed on almost every computer (98.9%), but Adobe AIR probably isn't installed on your computer, unless you've previously used an Adobe AIR app.

To run original JavaScript Cappuccino applications, all you need is a web browser that supports JavaScript (All current versions of Internet Explorer, Firefox, Safari, and Google Chrome), and has it enabled.

To build Cappuccino itself, read more here: [Getting and Building the Source](http://wiki.github.com/cappuccino/cappuccino/getting-and-building-the-source>).

If you're using Windows, you'll also need [Cygwin](http://www.cygwin.com/).

Finally, if you want to easily stay up to date with the latest developments and contribute your work back to the Cappuccino community, you'll want to [install Git](http://git-scm.com/).

Getting Started
---------------
These instructions are for building a development copy of Cappuccino. If you'd just like to get started using Cappuccino for your apps, you should instead download a pre-compiled copy of Cappuccino from:

  <http://github.com/XTREME104/cappucino/downloads>

To build Cappuccino from source, check out the most recent stable version from GitHub:

    $ git clone git://github.com/XTREME104/cappuccino.git (git)

or download the zipball of the most recent source code:

  <http://github.com/XTREME104/cappuccino/zipball/master> (zip)

If this is your first build and your system does not have narwhal and jake installed, run the bootstrap script to install it and all of its dependencies:

    $ ./bootstrap.sh

Then, simply type `jake` from within the root of the Cappuccino directory. This will build a "release" copy of the frameworks. Typing `jake debug` will build a debug version.

`jake install` will build Cappuccino and associated tools and install them for general use.

Editors
-------
The Cappuccino TextMate Bundle: <http://github.com/malkomalko/Cappuccino.tmbundle>.

The Cappuccino Xcode Plugin: <http://github.com/rbartolome/xcode-cappuccino>.

Getting Help
------------
If you need help with Cappuccino, you can get help from the following sources:

  - [FAQ](http://cappuccino.org/discuss/faq.php)
  - [Documentation](http://cappuccino.org/learn/)
  - [Cappucino for ActionScript Wiki](http://github.com/XTREME104/cappuccino/wikis)
  - [Original Cappuccino for JavaScript Wiki](http://github.com/cappuccino/cappuccino/wikis)
  - Mailing Lists:
    - [Objective-J](http://groups.google.com/group/objectivej)
    - [Objective-J Developers](http://groups.google.com/group/objectivej-dev)
  - IRC: irc://irc.freenode.net#cappuccino

If you discover any bugs, please file a ticket at:

  <http://github.com/XTREME104/cappuccino/issues>

License
-------
This library is free software; you can redistribute it and/or modify it under
the terms of the GNU Lesser General Public License as published by the Free
Software Foundation; either version 2.1 of the License, or (at your option)
any later version.

This library is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more
details.

You should have received a copy of the GNU Lesser General Public License along
with this library; if not, write to the Free Software Foundation, Inc., 51
Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA