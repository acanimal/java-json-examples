# Java JSON Examples

This repository contains code demonstrating the use of the GSON libraries to read both in object and stream mode.

Similarly to XML DOM and SAX parse modes, JSON files can also be read both thinking in object model or streaming.

Because the object model parses the whole JSON file and loads it in memory it is extremely memory consuming. On the other hand, streaming mode reads the file as a data stream and offers possibility to work with JSON attributes and object in a *low level* or mix with the object mode and read a concrete object.
