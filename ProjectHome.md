A tool to generate Python bindings for C/C++ code.  It is itself written in Python (unlike almost any other tool out there), lending it the powerful ability of making it possible to extend or tweak the code generator without loss of mental sanity.  It generates extension modules that are [small and fast](http://telecom.inescporto.pt/~gjc/pybindgen-benchmarks/).

PyBindGen is highly portable:
  * The (optional) pygccxml-based scanner generates just Python code describing the API;
  * PyBindGen as a module is just a bunch of .py files that can be shipped inside another project and used without installation;
  * It generates C/C++ code that is self-contained at compile-time (only Python headers are required) and at run-time (no special library or Python module is required)

See the documentation for a list of supported features and supported Python versions.

For discussion, Python's [C++ SIG](http://mail.python.org/mailman/listinfo/cplusplus-sig) mailing list can be used.  Alternatively, launchpad's [Answers](https://answers.launchpad.net/pybindgen) can be used instead.

To install the newest pybindgen version from the bazaar repository, you can run the command:
```
pip install -e "bzr+https://code.launchpad.net/~gjc/pybindgen/trunk#egg=pybindgen"
```
&lt;wiki:gadget url="http://www.ohloh.net/p/15916/widgets/project\_partner\_badge.xml" height="53"  border="0" /&gt;
