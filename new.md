# Scaladoc-user-guide

Scaladoc is a Documentation generating tool used in scala. It reads the specially formatted comments in the source code and generates the compiled documentation.This documentation provides useful information of all the packages, classes, methods, traits and objects used in source code. 

Use the following steps to generate documentation using scaladoc.

1. Use Scaladoc comment block which starts with /** and ends with */ as follows.

````scala
/** Start the comment here
  * and use the left star followed by a
  * white space on every line.
  *
  * Even on empty paragraph-break lines.
  *
  * Note that the * on each line is aligned
  * with the second * in /** so that the
  * left margin is on the same column on the
  * first line and on subsequent ones.
  *
  */
````


