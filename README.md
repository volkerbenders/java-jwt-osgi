# Java JWT OSGi #

This bundle encapsules the third party dependencies into an OSGi bundle exporting only the [java-jwt](https://github.com/auth0/java-jwt) packages in its MANIFEST.MF

To create the bundle just type ``mvn install`` and take a look in your target folder.

## Changelog
- cloned
- added `com.auth0.jwt.algorithms` to list of expoerted packages. This was required for my token generator to work with aem 6.1

# EOF
