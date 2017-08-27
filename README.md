eval-issue-openfl
=================

A small project to reproduce a problem with Haxe4 compilation. Tested with development versions of lime and openfl.

To test call:

    openfl build html5


Build & runs successfully with Haxe3, with Haxe4 compilation shows error messages and fails:

    hendrik:eval-issue-openfl hendrik$ openfl build html5
    /Dev/haxe/lime/lime/utils/Bytes.hx:23: characters 10-43 : haxe.io.Bytes does not have a constructor
    /Dev/haxe/openfl/openfl/utils/ByteArray.hx:286: characters 3-26 : haxe.io.Bytes does not have a constructor
    /Dev/haxe/openfl/openfl/utils/ByteArray.hx:786: characters 3-4 : Unknown identifier : b
    Field index for length not found on prototype haxe.io.Bytes
