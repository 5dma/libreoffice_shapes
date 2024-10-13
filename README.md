# Libre Office Shapes

A collection of source files for complex, native shapes for Libre Office Draw.

## Generating a Draw file from the source

The following instructions pertain to the shapes for theater lighting. Similar instructions apply to the other shape libraries.

1. Change to the desired directory, such as `Theater_Lighting/`.
1. Run the following command:

```zip -r TheaterLighting.odg mimetype content.xml styles.xml meta.xml settings.xml Thumbnails/ Configurations2/ META-INF/ Pictures/```

1. Open the file `TheaterLighting.odg` in Draw.


## Bug

A change in the way Draw renders Bezier curves causes the shapes to appear incorrectly.
