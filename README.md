# obuildfactory

This GitHub project  provides build scripts for OpenJDK 7, 8, 8+Lambda, 8+Jigsaw.

These scripts add goodies like :

* ROOT CA generation, update and inclusion
* FreeType build and embedding on platform where minimal requirements are not met.
* Native packages support, aka Linux RPMs up to trusted Yum repository population.
* OSX DMG for easy install via drag&drop


You could use these scripts from a Jenkins Powered environment to setup a Continuous Integration chain or standalone for one shot builds.

Initialy planned for Linux, it will also include Mac OSX scripts from [openjdk-osx-build](http://code.google.com/p/openjdk-osx-build/) so OSX users could produce their own packages

# documentation

[Building and packaging OpenJDK7 for OSX](https://github.com/hgomez/obuildfactory/wiki/Building-and-Packaging-OpenJDK7-for-OSX)

