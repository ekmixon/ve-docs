## ve-map-layer

The map shown for an active element can be augmented with one or more layers.  Two types of layers are currently supported.

### ve-map-layer attributes

- __type__:  `mapwarper` or `geojson`.  Defines the specific layer type.
- __title__:  The title attribute serves a couple purposes for map layers.  First, it is used a the label on map controls that enable/disable MapWarper layers and control the layer opacity.  When the layer type is geojson the title, when provided, will override any predefined labels in the GeoJSON file when displaying location labels on a map.  Note that when multiple features (and labels) are defined in a single GeoJSON file the title value will be used once for the aggregate features.
- __url__:  URL to a GeoJSON file.  This attribute is only used when the layer type is `geojson`.  This can be a relative URL (for example, `geojson/portugal.json`) if the geojson file is located in the same Github repository as the essay.  If not, the URL must be absolute.
- __mapwarper-id__:  Defines the overlay ID when the layer type is `mapwarper`
- __active__:  One of `true` (default if attribute is not provided) or `false`.  This attribute defines whether the layer is activated on the map when initially displayed.  In either case the user can toggle individual layers on/off using controls on the map.
