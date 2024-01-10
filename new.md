# Scaladoc-user-guide

Scaladoc is a Documentation generating tool used in scala. It reads the specially formatted comments in the source code and generates the compiled documentation.This documentation provides useful information of all the packages, classes, methods, traits and objects used in source code. 

Use the following steps to generate documentation using scaladoc.

__1. Use Scaladoc comment block which starts with /** and ends with */ as follows.__

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

__2.  Put Scaladoc comments above each following field in the source code with the important details relevant to each field.__

__Packages-__
- Overview of the package(What the package is about)
- Classes included in the package(Overview to major classes with basic examples to use in the package, reference the any classes with square bracket notation)

__Classes__
- Functionality of the class
- Mention what the constructor does with the `@constructor` tag
- Define the Parameters in the constructor with `@param` tag
- Document type parameters using @tparam tag

````scala
/** A person who uses our application.
 *
 *  @constructor create a new person with a name and age.
 *  @param name the person's name
 *  @param age the person's age in years
 */
class Person(name: String, age: Int) {
}
````
Month    | Savings |
| -------- | ------- |
| __January__  | $250    |
| \_\_February\_\_ | $80     |
| \`March\`    | // all on one line<br> {{{ if (foo) bar else   baz }}} <br><br> //Multiline code elements <br> bergehge |
| list   | /** Unordered list(bullet list) <br> * <br> *    - first item <br> *     - second item <br> *          - sub item <br> *        - another sub item <br> *      - third item <br> * <br>* Ordered List(Numbered list) <br> *  <br> *     1. first item <br> *    1. second item <br> *         i. sub item <br> *          i. another sub item <br> *   1.third item |
| list2   | >/** Unordered list(bullet list) >> * >> *    - first item >> *     - second item <br> *          - sub item <br> *        - another sub item <br> *      - third item <br> * <br>* Ordered List(Numbered list) <br> *  <br> *     1. first item <br> *    1. second item <br> *         i. sub item <br> *          i. another sub item <br> *   1.third item |

uyllil;






