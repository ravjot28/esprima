**Q: Why does `parse()` function throw an exception?**

A: Either it can't understand the code because of some syntax error or there is a bug in the parser.
If the code is valid but an exception is thrown, please [file an issue](http://code.google.com/p/esprima/issues/entry).

**Q: How fast is the parsing?**

A: It depends on the browser and the machine, simply run [the benchmarks suite](http://www.esprima.org/test/benchmarks.html) to see how fast various popular JavaScript libraries are parsed. There is also a [comparison test page](http://esprima.org/test/compare.html) to find out how Esprima scores compared with other parsers.

![https://lh5.googleusercontent.com/-Nl-Eu891bOA/TvoP7IhiSqI/AAAAAAAACak/Q-R17yic-m8/s800/esprima_compare.png](https://lh5.googleusercontent.com/-Nl-Eu891bOA/TvoP7IhiSqI/AAAAAAAACak/Q-R17yic-m8/s800/esprima_compare.png)