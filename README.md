# graphics-demo

Simple snap for glxgears, vkcube, glxinfo, and vulkaninfo utilizing the [gaming-graphics-core22 content snap][gaminggraphics].

Based largely on the [Steam snap](https://github.com/canonical/steam-snap).

## Using [gaming-graphics-core22][gaminggraphics]

### Connect

Connect gaming-graphics-core22 to the graphics-demo snap with

```
snap connect graphics-demo:gaming-mesa gaming-graphics-core22
```

### Switch Channels

Switch gaming-graphics-core22 channels with

```
snap refresh gaming-graphics-core22 --channel <channel>
# replace <channel> with kisak-turtle, kisak-fresh, or oibaf-latest
```



[gaminggraphics]: https://github.com/canonical/gaming-graphics/