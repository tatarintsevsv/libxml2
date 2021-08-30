# libxml2
modiied libxml2. based on libxml2-2.9.9

Original library can be found at xmlsoft.org

Added Annotation creation during validation by using validation option xmlSchemaSetValidOptions(ctxt,XML_SCHEMA_VAL_ANNOT_CREATE);

XSD element annotations (<xs:annotation><xs:documentation>element annotation</xs:documentation></xs:annotation>) appends to document as new comment nodes.

![изображение](https://user-images.githubusercontent.com/63135776/131288390-f44c6101-f17b-46e4-891f-bc353fcea514.png)
