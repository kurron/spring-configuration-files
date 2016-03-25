#Overview
This project holds all the configurations for the various projects that use the Spring Configuration server.

#Prerequisites
None.

#Building
Since these are simply data files consumed by another project, there is nothing to build.

#Installation
Nothing to install.

#Tips and Tricks

##Supporting Different Spring Profiles
The Spring Configuration server will combine multiple configuration files using the following rules:

* all files named `application.yml`
* files in the `${application}/${profile}` folder.  Where `application` maps to `spring.application.name`
and `profile` maps to `spring.active.profiles` on the client.
* application-specific are typically named `${application}.yml`

#Troubleshooting

#License and Credits
This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

#List of Changes

