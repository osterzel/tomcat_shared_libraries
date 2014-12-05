## Generating packages

This build will generate an rpm or deb package with a set of libraries for
putting into tomcat

to generate for debian based systems
./gradlew buildDeb

to generate for rpm based systems
./gradlew buildRpm

This will generate a package which will extract to /srv/tomcat/catalina/libs
