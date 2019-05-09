Clone of Love 2D version 0.10.0

Libluasocket fixed to use LuaJIT 2.1+

Compilation
-----------

### Windows
Follow the instructions at the [megasource][megasource] repository page.

### *nix
Run `platform/unix/automagic` from the repository root, then run ./configure and make.

	$ platform/unix/automagic
	$ ./configure
	$ make
	$ /src/love

### Mac OS X
Download the required frameworks from [here][dependencies] and place them in `/Library/Frameworks/`.

Then use the Xcode project found at `platform/xcode/love.xcodeproj` to build the `love-macosx` target.

### iOS
Download the required libraries from [here][dependencies-ios] and place the `include` and `libraries` folders
into the `platform/xcode/ios` folder.

Then use the Xcode project found at `platform/xcode/love.xcodeproj` to build the `love-ios` target.

See `readme-iOS.rtf` for more information.

### Android
Visit the [Android build repository][android-repository] for build instructions.

Dependencies
------------

- SDL2
- OpenGL 2.1+ / OpenGL ES 2+
- OpenAL
- Lua / LuaJIT / LLVM-lua
- FreeType
- PhysicsFS
- ModPlug
- mpg123
- Vorbisfile
- Theora

[site]: http://love2d.org
[wiki]: http://love2d.org/wiki
[forums]: http://love2d.org/forums
[irc]: irc://irc.oftc.net/love
[dependencies]: http://love2d.org/sdk
[dependencies-ios]: https://bitbucket.org/rude/love/downloads/love-0.10.0-ios-libraries.zip
[megasource]: https://bitbucket.org/rude/megasource
[builds]: http://love2d.org/builds
[stableppa]: https://launchpad.net/~bartbes/+archive/love-stable
[unstableppa]: https://launchpad.net/~bartbes/+archive/love-unstable
[aur]: http://aur.archlinux.org/packages/love-hg
[love-experiments]: https://bitbucket.org/bartbes/love-experiments
[codestyle]: https://love2d.org/wiki/Code_Style
[android-repository]: https://bitbucket.org/MartinFelis/love-android-sdl2
