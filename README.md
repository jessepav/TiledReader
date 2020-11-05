TiledReader is a simple Java library for reading information from files created with the map editor Tiled (https://www.mapeditor.org/). TiledReader makes the internal structure of Tiled map, tileset, and template files easy to navigate, but it cannot load image data (only report paths to image files), and it cannot render Tiled maps by itself. Thus, TiledReader is most appropriate when you want to use Tiled in combination with existing graphics code.

#### jessepav/TiledReader

This fork makes TiledReader Java 7 compatible.

You can build a jar with Ant, by running

```
ant build.all.artifacts
```


<!-- :wrap=soft: -->