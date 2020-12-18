# The Parts of an Essay

Essays written for print often share similar parts, such as:

* A Title
* An Author
* A description or abstract
* Sections
* Paragraphs
* Footnotes/Endnotes/References

All of those parts can also be found in visual essays, but also include features such as:

* Images and Image Galleries
* Maps and Layers
* Linked Open Data
* Network Graphs

To create these features, a visual essay depends on some level of coding that describes for readers what should appear on the screen at any given time. Our goal in creating the Visual Essay Tool has been to balance the performative possibilities of your essay with the complexity of code. In doing so, we have sought to tuck code under the hood that the average scholar may find overwhelming, yet sufficiently expose the levers and buttons that are likely to help make sophisticated arguments. We create this balance—between accessibility and complexity—from author feedback. So please reach out if you feel like we're holding you back!

The structure of a visual essay is very similar to a traditional printed essay. They begin with descriptive data, transition into the argument body, and end with references. Here are the parts you can expect to see in the order they appear:

1. **Configuration Tag** Contains basic information about the essay such as title, author, and visual features
2. **Linked Data Tags** The concepts in the essay that have linked open data attached to them.
3. **Body** The main text of the essay broken up into sections by headings. Each heading can have visualizations attached such as images and maps. When the reader scrolls to the next heading, the visualizations are automatically replaced.
4. **References** The final section containing all the footnotes for the essay. These footnotes could be in any citation format and may include direct links to other sources.

# The Configuration Tag

The `param ve-config` tag is not technically required for an essay to render, but it supplies crucial information that any serious essay would include. The form of the configuration tag is:

`<param ve-config attribute1="value for this attribute">`

Note that the tag begins with a left caret (<) and ends with a right caret after the final attribute (>). It can contain multiple attribute/value pairs. Each attribute can be spaced out on a single line, but they are often clearer when formed into a vertical list like so:

![An example configuration tag](config-tag.png)

The value for a given attribute is always enclosed in double quotations marks ("). In this example we can see the following *attributes* are defined for this essay:

|Attribute|Description of the value|Effect for Readers|
|---|---|---|
|title|The title of your essay|Displayed at the top of your essay|
|banner|The URL of your banner image|Displayed at the top of your essay|
|layout|Specify a vertical essay with `vtl`|Your essay will use a vertical orientation|
|num-maps|The number of maps in your essay|Displayed at the top of your essay|
|num-images|The number of images in your essay|Displayed at the top of your essay|
|num-primary-sources|The number of primary sources in your essay|Displayed at the top of your essay|
|author|That's probably you!|Displayed at the top of your essay|

# Linked Open Data Tags

