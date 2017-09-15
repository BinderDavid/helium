![Helium Logo](http://www.cs.uu.nl/people/jur/Helium_0300pix.jpg)

### Helium

Helium is a functional programming language (a subset of Haskell) and a
compiler designed especially for teaching. The main developers and
initiators are Arjan van IJzendoorn, Rijk Jan van Haaften, Bastiaan
Heeren and Daan Leijen. Currently, Jurriaan Hage, and Bastiaan Heeren
maintain the compiler and associated tools. For more information about
Helium contact [us](mailto:helium@cs.uu.nl).

On August 2, 2014, we first uploaded cabal installs for the packages
that make up the Helium compiler to
[Hackage](https://hackage.haskell.org/package/helium). This means that
you can install the latest version of Helium by running
    cabal install helium
    cabal install lvmrun

The former of the two is the compiler (which will probably install a few
more packages, like Top and lvmlib), the second is the run-time. You can
then test the installation by running the program *texthint* and
evaluating a few expressions. The system is known to install with GHC
7.6.3 and GHC 7.8.x.

Other kinds of downloads are not supported anymore, and we advise
against using them.

### Hint

Helium 1.8.1 and higher again have support to work with the graphical
Java-based programming environment Hint, originally developed by Arie
Middelkoop.

[**Download the Hint 1.8.1 jar
file**](http://www.cs.uu.nl/people/jur/Hint-1.8.1.jar)

The program can be run from the command line in the usual way

       java -jar Hint-1.8.1.jar

Of course, you must have the Java runtime installed on the system. Note
that you need Hint version 1.8.1 or higher for this to work.

Hint is not available through Hackage. The sources of Hint are publicly
available from the svn repository that also stores the source code of
the Helium compiler and all associated tools.

### Beyond the standard distributions

All software associated with Helium is available from a publicly
available git repository at <https://github.com/Helium4Haskell/>, in
particular the repositories

-   [helium](https://github.com/Helium4Haskell/helium)
-   [hint](https://github.com/Helium4Haskell/hint)
-   [vm](https://github.com/Helium4Haskell/lvm)
-   [Top](https://github.com/Helium4Haskell/lvm)

These source distributions are to be used at your own risk.

### Plans for the future

-   check documentation consistency
-   performance bug fix type inferencer
-   add type classes in full

If you think you can do something for us on the above, please contact
[us](mailto:helium4haskell@gmail.com).
