# Visual essay tags

Essay visualizations are created (and optionally controlled) through the addition of special HTML tags to the essay markdown text.  Two different HTML tags are used.

- The __param__ tag is used to define visualizations that are associated with an essay section or paragraph.  The `param` tags all start on a new line and include attributes defining the specific visualization to create and all required options.
- The __span__ tag is used to wrap sections of text in the essay to associate the text with an entity or to use the text as a interaction trigger.  An example of an interaction trigger would be connecting a location reference in the essay text to an interaction that causes the map to "fly to" a specific location when the user clicks on or hovers over the "spanned" text in the essay.

HTML tags begin with the `<` character and end with the `>` character.  The text after the `<` character and before the first space define the tag name.  The HTML language defines many tags but the visual essay tool only uses the `param` and `span` tags.  Both of these are standard HTML tags that have been extended for use by the visual essay tool.  In the case of the `param` tag a visual essay type attribute and optional options attributes are used to define the type of visualization generated.  The visual essay type attribute starts with `ve-` and defines the specific component used to render the visualizaiton.  Below are a few commonly used `ve` type attributes.

- `ve-image`
- `ve-map`
- `ve-video`

## Configuration and data tags

- [Essay configuration](ve-config)
- [Entity declaration](ve-entity)

## Visualization component tags

- [Image viewer](ve-image) - <i class="fas fa-image"></i>
- [Map viewer](ve-map) - <i class="fas fa-map-marker-alt"></i>
- [Map layer](ve-map-layer) - <i class="fas fa-map-marker-alt"></i>
- [Video viewer](ve-video) - <i class="fas fa-video"></i>
- [Network viewer](ve-network) - <i class="fas fa-chart-network"></i>
- [Plant specimen viewer](ve-plant-specimen) - <i class="fas fa-seedling"></i>
- [Tabular data viewer](ve-table) - <i class="fas fa-table"></i>
- [Knightlab timeline viewer](ve-knightlab-timeline) - <i class="fas fa-history"></i>
- [Graphic viewer](ve-graphic) - <i class="fas fa-file-image"></i>
- [Storiiies viewer](ve-storiiies) - <i class="fas fa-book"></i>

