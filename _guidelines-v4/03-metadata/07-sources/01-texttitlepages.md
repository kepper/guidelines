---
sectionid: textTitlePages
title: "Title Pages"
version: "v4"
---

A specialized element is furnished for the capture of titlepage information.

{% include desc elem="titlePage" %}

The {% include link elem="titlePage" %} element, modelled after a similar element in Encoded Archival Description (EAD), may occur within the textual matter preceding or following the musical content of the encoding. Since a diplomatic transcription of the titlepage is often necessary to accurately identify musical material contained within a source, {% include link elem="titlePage" %} may also be used within the metadata header as a child of the {% include link elem="physDesc" %} element.

Detailed analysis of the title page and other preliminaries of older printed books and manuscripts is of major importance in descriptive bibliography and the cataloging of printed books. The following elements are suggested as a means of encoding the major features of most title pages for faithful rendition:

{% include desc elem="titlePage" %}
{% include desc elem="p" %}
{% include desc elem="table" %}
{% include desc elem="list" %}
{% include desc elem="quote" %}
{% include desc elem="lg" %}

The following example shows the encoding of the title page of Vaughan Williams' *On Wenlock Edge*. Note the use of the {% include link elem="lb" %} element to mark the line breaks present in the original.

{% include mei example="text/text-sample371.xml" valid="" %}

The physical rendition of title page information is often of considerable importance. One approach to this requirement would be to use the {% include link elem="rend" %} element, described in chapter {% include link id="sharedTextRendition" %} to specify the rendition of each of the components of the title page. Another would be to employ a CSS stylesheet. Finally, a module customized for the description of typographic entities such as pages, lines, rules, etc., bearing special-purpose attributes to describe line-height, leading, degree of kerning, font, etc. could be employed.
