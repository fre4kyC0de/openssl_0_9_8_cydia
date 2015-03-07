Patches to OpenSSL 0.9.8 to create a Cydia deb

Replace the files after configuring OpenSSL 0.9.8ze.

armv7
=====
For armv7 run
./config shared
./Configure darwin-i386-cc shared --prefix=/usr --openssldir=/usr/lib/ssl 

arm64
=====
For arm64 run
./config shared
./Configure darwin64-x86_64-cc shared --prefix=/usr --openssldir=/usr/lib/ssl

Then use "make" to compile.

You may use my fork of OpenSSL, too.
