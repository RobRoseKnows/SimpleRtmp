# SimpleRtmp - Client-side RTMP library for Java

## Original Description

SimpleRtmp is a Java library for building RTMP client applications.
It was written entirely from scratch to avoid issues I encountered with existing Java
RTMP libraries - namely that most of them are based off the (excellent) Red5 Flash Media
Server's codebase, which requires a working NIO implementation (Android 2.2, I'm looking at you).
I also did not like all of the external dependencies introduced by this. Whilst it 
is fine for a server, I needed something more lightweight.

This library focuses *only* on client-side RTMP implementation (and
is very unlikely to ever have a server-side component); it currently also only allows
for audio playback (as this is what I needed it for). 

Patches are welcome!

## This Fork

I am editing the [original repository][1] by @faucamp to work with Gradle so that it can be used
in other projects, especially on Android, more easily. If anyone would like to help the
conversion, that would be nice as I am not really familiar with it.

## License information

Copyright (C) 2013-2018 Francois Aucamp, Rob Rose
See [contributors page][2] for all authors and contact information.

License: GNU Lesser General Public License, version 3 or later; see [LICENSE.md][3]
         included in this archive for details.

[1]: https://github.com/faucamp/SimpleRtmp
[2]: https://github.com/RobRoseKnows/SimpleRtmp/graphs/contributors
[3]: https://github.com/RobRoseKnows/SimpleRtmp/blob/master/LICENSE.md