<param ve-config layout="vtl">

# Adding a Map to Your Essay

<param ve-map center="Q12439" title="Detroit" zoom="12" prefer-geojson>

To include a basic map in a section of your essay, use the `<param ve-map>` tag:

`<param ve-map center="Q12439" title="Detroit" zoom="12">`

The Wikidata entity identifier for Detroit is "Q12439". We supply this identifier to the `center` attribute. In this example, we have also included a `title` attribute so we can remember what the entity is. This is only for our benefit; it doesn't change the map in any fashion. We could, for example, have made the title "American-Canadian Border" and it would have pointed to the same entity location for Detroit.

Finally, we have included a zoom level of "8". As that number increases, we will zoom in closer to street level. As it decreases, our map will show whole countries, continents, and then the globe.

After the map has rendered at our defined level, readers also have the option to zoom in, zoom out, and move the map at will.

# Ann Arbor

## Overview

<param ve-entity eid="Q12439" title="Detroit">
<param ve-entity eid="Q485172" title="Ann Arbor">
<param ve-entity eid="Q871265" title="East Lansing">

Ann Arbor is a city in the U.S. state of Michigan and the county seat of Washtenaw County. The 2010 census recorded its population to be 113,934. It is the principal city of the Ann Arbor Metropolitan Statistical Area, which encompasses all of Washtenaw County. Ann Arbor is also included in the larger Greater Detroit Combined Statistical Area.[^1]
<param ve-map primary center="Q485172" zoom="12" prefer-geojson>


____
[<- Home](https://docs.visual-essays.app/)
