Description
==============

This is a companion package to [Teaspoon](https://teaspoontda.github.io/teaspoon/), and includes the modules of teaspoon that use zigzag persistence, and rely on [dionysus](https://pypi.org/project/dionysus/).  Many Teaspoon users did not need the full install that included additional system dependencies.

Full documentation of this package is available [here](https://teaspoontda.github.io/spork/). The full documentation includes information about installation, module documentation with examples, contributing, the license, and citing spork.

The code is a compilation of work done by [Elizabeth Munch](http://www.elizabethmunch.com) and [Firas Khasawneh](http://www.firaskhasawneh.com/) along with their students and collaborators.  People who have contributed to spork include:

- [Audun Myers](https://www.audunmyers.com)
- [Melih Yesilli](https://www.melihcanyesilli.com)
- [Sarah Tymochko](https://www.egr.msu.edu/~tymochko/)
- [Danielle Barnes](https://github.com/barnesd8)
- [Sunia Tanweer](https://stanweer1.github.io/)
- [Max Chumley](https://www.maxchumley.com/)
- [Ismail Guzel](https://ismailguzel.github.io/)

We gratefully acknowledge the support of the National Science Foundation, which has helped make this work possible.

Installation
=============
To install this package, both boost and CMake must be installed as system dependencies.  For boost see for [unix](https://www.boost.org/doc/libs/1_66_0/more/getting_started/unix-variants.html) and [windows](https://www.boost.org/doc/libs/1_62_0/more/getting_started/windows.html).  For mac, you can run ``brew install boost`` if using homebrew as a package manager.  For CMake see [here](https://cmake.org/install/).

The spork package is available through pip install with version details found [here](https://pypi.org/project/spork/).
The package can be installed using the following pip installation:

	``pip install spork-tda``

To install the most up-to-date version of the code, you can clone the repo and then run::

  ``pip install .``

from the main directory.  Note that the master branch will correspond to the version available in pypi, and the test_release branch may have new features.

Please reference the requirements page in the [documentation](https://teaspoontda.github.io/spork/) for more details on other required installations.

Contacts
=============
* Liz Munch: [muncheli@msu.edu](mailto:muncheli@msu.edu).
* Firas Khasawneh: [khasawn3@egr.msu.edu](mailto:khasawn3@egr.msu.edu).
