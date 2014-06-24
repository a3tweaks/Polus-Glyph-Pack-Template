Polus Glyph Pack Template
=========================

Basic template for the creating additional glyph packs for use in Polus.

Glyphs
======

Glyph's need to use the @2x file extension as well as have an 88px square canvas (technically 44pt at non-retina size) so that they appear properly in Quick Launch.

You can add glyphs with a generic name (e.g. Music@2x.png) or you can also add them using an app's specific identifier (e.g. com.apple.Music@2x.png) so that they are automatically searched for and used as a default if the user doesnt have an alternative set.
Note, this functionality will only take place when your Glyph Pack is ordered properly in the 'Arrange Glyphs' section as the glyphs are searched in a manner similar to WinterBoard.

Usage
=====

Your Glyph Pack's bundle needs to be placed in /Library/Polus/Glyph Packs in order for Polus to recognise it and use it acccordingly and be sure to modify both the *.bundle name and the contents of the Info plist file to suit your uses.
Both the Bundle Display Name and Bundle Identifier are used throughout Polus and presented to the user so ensure that these are properly set.

In addition, try to ensure that the bundle identifier matches the identifier used in cydia so that we can accurately indicate wether your pack is installed should it be added to the Featured section within Polus.

Also, please add a dependancy for com.a3tweaks.polus in your packages control file to ensure that the Glyph Pack makes sure that the official version of Polus is installed.
