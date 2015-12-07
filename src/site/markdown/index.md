# Design Patterns for files

This is an implementation of the [Java Patterns][java-patterns] project for various types of files.

These implementations are for the Parser and Outputter interfaces, and allow transforming a Java object into an XML or YAML file, and vice versa.

## The patterns in the library

The implementations are not following any concrete book or specification, they just mix what I need with a general idea of what they are expected to do.

- The [Outputter][docs-outputter] implementations offer a way for creating XML and YAML files from a Java object.
- The [Parser][docs-parser] implementations create Java objects from XML files.

[java-patterns]: https://github.com/bernardo-mg/java-patterns

[docs-outputter]: ./outputter.html
[docs-parser]: ./parser.html
