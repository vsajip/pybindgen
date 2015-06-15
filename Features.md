# List of features supported by PyBindGen #
  * Generates clean C or C++ code, almost as clean as what a human programmer would write;
  * Generation is controlled exclusively by a Python API
    * No limited command-line interface or yet another interface definition file format;
  * Optional support for robust error handling
    * Don't traceback on errors, keep wrapping a subset of the API as much as possible;
  * Generated code is self contained and does not depend on any library
    * Except for Python itself and the library you're trying to wrap, of course;
  * C functions and C++ classes / structures;
  * Direct access to structure/class fields;
    * Even has support for class static member variables;
  * Many different C++ object ownership transfer options, smart pointers, and reference counting;
  * "in", "out", and "inout" parameters and, consequently, multiple return values;
  * C++ virtual methods, which can be implemented in Python subclasses;
  * Overloaded functions/methods/constructors;
  * Automatic type narrowing on pointer-to-object return values, using C++ RTTI;
  * C++ implicit conversions in parameters of functions, methods, and construtors;
  * Translation of C++ exceptions to Python
  * Multiple inheritance;

# Notable features NOT (yet) implemented #
  * Callbacks (not automatically, custom callback handling code can be written, though).
  * Translation of Python exceptions to C++
  * Translation of `__special_methods__` into python PyType tp\_xxx is not supported, with some exceptions.

More features not implemented or known problems can be found by [searching the bug tracker](https://bugs.launchpad.net/pybindgen/+bugs?).