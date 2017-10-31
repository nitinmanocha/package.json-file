# package.json-file
A package is a collection of number of modules that is published so that others can use it. It is described by its data and version number. A tool “ package manager” is used to install a package into system to use a package.
The json in package.json file stands for Java Script Object Notation. It is used in transmission of data between server and web applications.
Dependencies
the modules which are used by other modules are known as dependencies.all the dependencies in package.json file contains a version number. for example:
{ “dependencies”
{
“cors:2.8.1”
}}
In this, 2.8.1 is the version number.
Use of tilde (~) and caret (^)
the tilde matches the most matched vesion of dependency where as the caret will update the dependency to most updated version.

— — save
During installation of dependency using NPM, if we don’t use — save , then the dependency won’t be loaded into the package.json file and will be kept seperate.
