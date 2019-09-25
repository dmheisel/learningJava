# learningJava

## Installing

To install, first make sure brew is up to date

`brew update`

because java is not open source, we use cask to install it.

`brew tap caskroom/cask`

then use cask to install java

`brew cask install java`

takes a little while, so be patient!  To use VSCode, grab the extension Java Extension Pack that should get everything you need.

## Compiling before running!


## Variables

Variables are defined with the type right away, such as:
`String taco = "taco string"`

String is the type of the variable
taco is the variable name
taco "string" is the value of that variable

Arrays are declared using [] after the type of element that array will contain, like

`int[] myArray`

creates myArray as an array of integers.
Arrays also need to be instantiated with a length, like:

myArray = [10]

This creates an array that has storage for 10 items in it.


## Objects / Classes

Everything is a class!
So your files will contain one public class, with other methods or variables defined within that class.
Other classes can be created in the file, but only one is public
A simple Hello world looks like:


`public class HelloWorld {

  public static void main(String[] args) {
    System.out.println("Hello World!");
  }
}`
