This is a test repo for aquestion about th Hugo Static Site Generator

I'm trying to use a _content.gotmpl file to generate pages from an xml file.

My Problem is that not all of the info I need is in the xml.   For example, I want to add tags and a content descrption for some of the nodes  in the xml file. I can't edit the xml file directly as the XML file is produced elsewhere.  So, I add some related .MD files in the content/places/<node> folder.  My thought is that this can work as a page bundle for the content pages that are generated from the xml.

This is not working.  I guess I understand why... I'm mixing two method of creating page and it is sort of a chicken and egg scenario.

So, I guess my question is, how should I be doing this?
