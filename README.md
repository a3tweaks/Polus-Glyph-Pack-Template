Polus Glyph Pack Template
=========================

Basic template for the creating additional glyph packs for use in Polus.

Usage
=====

Be sure to modify both the *.bundle name and the contents of the Info plist file to suit your uses.
Both the Bundle Display Name and Bundle Identifier are used throughout Polus and presented to the user so ensure that
these are properly set.

You can add glyphs with a generic name (e.g. Music@2x.png) or you can also add them using an app's specific
identifier (e.g. com.apple.Music@2x.png) so that they are automatically searched for and used as a default if the user doesnt have an alternative set.
Note, this functionality will only take place when your Glyph Pack is ordered properly in the 'Arrange Glyphs' section
as the glyphs are searched in a manner similar to WinterBoard.
