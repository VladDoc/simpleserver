RegExp — Higher-level abstraction over PCRE2 with JIT support
=============================================================

More info to appear here...

.. * Important *:
   For some reason clang python bindings try to use default include
   "lib/clang/10.0.0/include" instead of "/lib/clang/10.0.0/include" which results in epic failure
.. Also here we need to pass arguments separated by comma
   Had to look through hawkmoth source to find this
.. Current directory '.' is not changed in process and exactly is what had been set in config
   (I had no time to check with other configs)

.. c:autodoc:: inc/regexp.h
   :clang: -I/lib/clang/10.0.0/include,-I../inc,-std=gnu17,-DHAWKMOTH

