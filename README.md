# upnp4j
A simple UPnP library for Java


## Maven/Gradle
You can download upnp4j from my maven repo: `https://maven.pkg.github.com/cyberflamego/upnp4j`
under the group `me.notom3ga`, artifact `upnp4j` and version `1.0`.
(Added my gh packages repo (with permission, see below) as the original one went down)
![image](https://user-images.githubusercontent.com/24910512/132849036-2d0de862-cc56-45b2-8ec3-6eab9229fee3.png)

## Usage
To open port 25565 with TCP use:
```java
UPnP4J.open(25565, Protocol.TCP);
```

## Inspiration
upnp4j is a continuation of [WaifUPnP](https://github.com/adolfintel/WaifUPnP),
which is licensed under LGPL 2.1.
