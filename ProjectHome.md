# LENA - RDF/Linked Data Browser #

LENA stands for LEns based NAvigator. A lens represents a particular view onto RDF data and is described by the [Fresnel Display Vocabulary](http://www.w3.org/2005/04/fresnel-info/). LENA enables viewing RDF data in your web browser, rendered according to the lens descriptions you provide. LENA supports the use of multiple lenses and indicates if they are available for a resource, so that a different view onto the same data is always just one click away!

To write lenses for complex RDF structures created through sophisticated ontology frameworks like [COMM](http://comm.semanticweb.org/) or [X-COSIM](http://isweb.uni-koblenz.de/Research/x-cosim), LENA supports [SPARQL](http://www.w3.org/TR/rdf-sparql-query/) selectors. As comprehensive query language for RDF, SPARQL complies to the requirements needed to select from these complex structured RDF graphs. While a Fresnel SPARQL selector is a designated Fresnel selector an implementation did not yet exist. LENA provides an extension to support Fresnel SPARQL selectors that is now integrated into the [Simile Fresnel engine](http://simile.mit.edu/wiki/Fresnel).

The data which shall be processed by LENA, can either be put into the provided directory or be accessed through a [Sesame](http://www.openrdf.org/) HTTP repository. Furthermore linked data can be browsed by entering a dereferenceable URI. For more information about the usage of LENA see the FAQ.

# Demo #

[View The Demo!](http://dom.uni-koblenz.de:8080/lena)

![http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/foaf_small.png](http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/foaf_small.png)
![http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/rss_small.png](http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/rss_small.png)
![http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/message_small.png](http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/message_small.png)

# Download And Installation, Links, FAQ #
[see Wiki](HOME.md)

# News #
#### LENA 1.1.1 ####
_16.09.2008_

Moved to Google Code, removed session problem and some bugs.

---

#### LENA 1.1.0 ####
_03.09.2008_

LENA is back in development featuring the new version 1.1.0. This version enables LENA to browse linked data, futhermore it adds pages support. Updated to Sesame 2.1.3.

---

#### LENA 1.0.2 ####
14.11.2007

Update to Sesama 2.0 beta 6. Demo server traffic restrictions removed.

---

#### LENA 1.0.1 ####
09.10.2007

LENA home page shortened. Abbreviation of property labels and property values (resources only) that have not been specified else by the Fresnel configuration.

---

#### LENA 1.0.0 Release ####
30.09.2007

First official version release of LENA.

---


# Acknowledgements #

This work was funded by the X-Media project (www.x-media-project.org) sponsored by the European Commission as part of the Information Society Technologies (IST) programme under EC grant number IST-FP6-026978.

![http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/x-media.png](http://www.uni-koblenz.de/FB4/Institutes/IFI/AGStaab/Research/lena/x-media.png)

Thanks to Ryan Lee for the support regarding the [SIMILE Fresnel engine](http://simile.mit.edu/wiki/Fresnel).

Thanks to Mark James for the icons on [famfamfam.com](http://www.famfamfam.com).