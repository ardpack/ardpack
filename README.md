# ardpack
## The Git Backed Arduino Library Package Manager

A common problem in developing libraries for the Arduino platform
is being able to use the library in multiple sketches while also actively
developing it. The problem results from the fact that installed libraries in the
Arduino `libraries` folder are often cached during the Arduino build process. As
a result, changes made to the libraries are not always reflected when the sketch
using the library is run again. The Arduino library manager provides basic
dependency management allowing users to search and download libraries hosted on
GitHub. However, there is no concept of a package or dependency where a library
can be "installed" on the system along with its dependencies. Moreover, the
Arduino build process forbids relative imports from directories outside the sketch
directory, where the `.ino` file is found. These restrictions in the
Arduino code compilation process leads to difficulty making larger projects
with a structured code base where libraries and modules can be used, actively
developed and updated easily without manually replicating the library code in
each sketch folder.


`ardpack` solves these problems by providing a full package
manager for Arduino projects, giving developers the ability to structure
their projects more efficiently and clearly using `ardpack` packages to specify
a list of dependencies. The end user is also able to install the package and its
dependencies automatically in the command line on a per project basis. `ardpack`
not only assists developers in structuring large Arduino projects but assists the end
user as well by streamlining the installation of any library and its
dependencies into a single command.

## Initializing an Project
TODO

## Installing Packages
TODO

## Removing Packages
TODO

## Creating a Custom Package
### Making a `.ardpack` File
### Specifying Dependencies
### Listing the Package to the Public

