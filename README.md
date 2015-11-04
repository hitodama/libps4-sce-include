libps4-sce-include
=====

> Imported by libps4-generator to generate libps4

# Description

This is the primary collection of SCE module headers, which are used to generate libps4. They are reverse engineered to mirror the functionality of the official SCE headers as close as possible for the purpose of study and compatibility (fair-use).

##Internals

For a list of potential headers (modules) to be included here see `sce.h` in libps4-boilerplate. If a header is not listed in sce.h, you need to add it, to enable its automated import by libps4-generator.

##Conventions and Versioning

Due to the fact that structures may change in an incompatible manner, we may benefit from versioning (e.g. macros). We may also want to define conventions to create a consistent look and feel.

##TODO
- Work out a convention for function declarations (if possible).
- Reverse engeneer, bruteforce etc. to find other symbols and declare them.
- Add browsable wiki, overview, describtions of modules and functions on github?

#Credits
The header creation is a community effort and people should be named here appropriately.

Most of the initial work here was done by CTurt I belive.
