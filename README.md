# mermaid-confluence-embed

mermaid-confluence-embed is a small snippet of HTML and javascript that allows adding a mermaid diagram to Confluence more easily within a Data Section macro

## Getting Started

### Prerequisites

mermaid-confluence-embed is built to be embedded in a Confluence page and as such requires a Confluence instance.

In addition you must have the [HTML Macro](https://bobswift.atlassian.net/wiki/spaces/HTML/pages/6422530/HTML+Macro) plugin installed, and support for including javascript enabled. You must also have the Data Section macro.

### Installing

Embed a Data Section macro on your Confluence page and add a Text Data field with the content type set to no-format. This field will hold your mermaid markup. Note that it must have a unique "Field Name" on the page. Add a HTML macro within the Data Section but after the Text Data field and configure the 'Location of HTML Data' field to the following:

```
#https://paulholmberg.github.io/mermaid-confluence-embed/embed_me.html
```

## License

This project is licensed under GPL3 - see the [LICENSE.md](LICENSE.md) file for details
