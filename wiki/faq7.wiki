Links can be set to LENA by pointing to the application root. There are 5 optional parameters: "lens", "resource", "uri", "location" and "sidebar".

The "lens" parameter tells the browser to render a given lens, the "resource" parameter can be added to display a special resource with that lens. The "resource" parameter alone shows a given resource through the DEFAULT lens. Additionally the "location" parameter has to be set to "local" when not browsing linked data.

The "uri" parameter can be used to add data from a dereferencable URI whereas the same URI is then used as "resource" parameter, the "location" parameter is set to "remote" by default. Values for all three parameters, "lens", "resource" and "uri" are encoded URIs.

With the "sidebar" parameter the sidebar can be hidden or shown. Values are "true" and "false", default is "true".