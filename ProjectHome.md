SimpleDOM is built upon SimpleXML and acts as a bridge providing DOM methods using SimpleXML's syntax. It also adds a bunch of convenience methods.

SimpleDOM is a single file with no dependencies. All you need to use it is include it and create `SimpleDOM` objects instead of `SimpleXMLElement` objects, or simply use `simpledom_load_string()` instead of `simplexml_load_string()`.

No user manual, but every method is documented in the phpDocumentor-generated manual included in the downloadable Zip file.