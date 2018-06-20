canadensys-web-theme
====================

Canadensys specific web components used to style our web applications.

You should not reuse this project as is but instead copy and change it to apply you [own styling](https://github.com/Canadensys/canadensys-web-theme/wiki/Create-your-own-theme) to some Canadensys web applications.

This library is currently used by [vascan](https://github.com/Canadensys/vascan), [narwhal-api](https://github.com/Canadensys/narwhal-api) and the [canadensys-explorer](https://github.com/Canadensys/canadensys-explorer).

## Usage
This component should be used as a WAR Overlay.

* [Using Gradle](https://github.com/scalding/gradle-waroverlay-plugin)
* [Using Maven](http://maven.apache.org/plugins/maven-war-plugin/overlays.html)

## Documentation
Please visit our [wiki](https://github.com/Canadensys/canadensys-web-theme/wiki).

## Artifact
This library is available on [Maven central](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22canadensys-web-theme%22) for Canadensys usage. If you want to adapt it to apply your own styling, it is recommended to follow [this guide](https://github.com/Canadensys/canadensys-web-theme/wiki/Create-your-own-theme).

## Install locally
```
mvn clean install
```

## Publish artifacts on Maven Central

Follow the same instructions as the [canadensys-web-core](https://github.com/Canadensys/canadensys-web-core#publish-artifacts-on-maven-central).

## Dependencies

The dependencies are implicit, they are not included in this project.
* Freemarker
* SiteMesh 3
