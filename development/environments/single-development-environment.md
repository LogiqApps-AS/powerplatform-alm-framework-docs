# Single Development Environment

## Developing Multiple Solutions in a Single Development Instance

This approach out of the box brings a lot of issues with development, testing, and deployment processes.

* There is no isolation between the unmanaged components and therefore it is easy for one or more components to be changed and included in more than one solution container
* When deploying to downstream environments, change in application behavior may not be predictable because they will be based on the order of solution import
* It is possible to get cyclic dependencies that prevent solutions from importing
