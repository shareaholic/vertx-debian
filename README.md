Files for making a Debian package of Vert.x
===========================================
1. Download Vert.x v1.3.1.final from http://vertx.io/downloads.html
2. Rename the downloaded file to `vert.x_1.2.3.final.orig.tar.gz` to comply Debian naming standards
3. Extract the tar file
4. Download slf4j and your preferred logging framework into lib.
5. Recreate the 'vert.x_1.3.1.final.orig.tar.gz' archive
3. clone this repository into the extracted tar as `debian/`
4. Run `$ dpkg-buildpackage`
