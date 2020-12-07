# How is a Visual Essay Written

The main text content is written in plain text with [markdown](https://www.markdownguide.org/getting-started/) markup for simple formatting.  External images, maps, and other data is linked to the text through the addition of specialized tags.

Users can add specialized visual items such as:

* Images
* Video
* Information from Knowledge Graphs
* Maps with informational layers

These visual items can appear automatically or be engaged by the reader. For example, if a location is mentioned in the text, a map could be displayed showing the location.  If a person is mentioned in the text, more information (including images) can be sourced from outside experts and displayed automatically.

# Bringing Knowledge Graph Data to your Essay

Additional data is typically sourced from Wikidata (the knowledge base behind Wikipedia). Wikidata is a Linked Open Data (LOD) knowledge base containing nearly 80 million entities (as of Feb 2020) and growing at the rate of nearly 1 million per month.  Each entity (person, location, organization, etc) in Wikidata is assigned a unique identifier commonly called a ‘Q’ ID as each of the identifiers starts with the ‘Q’ character followed by a number. Authors reference these identifiers to bring Wikidata information into their visual essay.

# Maps

Maps are added with a special tag that defines the latitude, longitude, and zoom level. Visual layers can be added to the map through mapwarper tiles and GeoJSON feature layers.
