<!-- This file contains a page fragment. Any changes will affect all pages that include it. -->

The following regular expression engines are included with InspIRCd:

Engine | Module                                  | Description
------ | --------------------------------------- | -----------
glob   | [regex_glob](/2/modules/regex_glob)     | Matches using a glob pattern.
pcre   | [regex_pcre](/2/modules/regex_pcre)     | Matches using a [PCRE](https://www.debuggex.com/cheatsheet/regex/pcre) regular expression.
posix  | [regex_posix](/2/modules/regex_posix)   | Matches using a [POSIX](http://man7.org/linux/man-pages/man7/regex.7.html) regular expression.
stdlib | [regex_stdlib](/2/modules/regex_stdlib) | Matches using a [C++11 `std::regex`](http://cpprocks.com/files/c++11-regex-cheatsheet.pdf) regular expression.
tre    | [regex_tre](/2/modules/regex_tre)       | Matches using a [TRE](https://laurikari.net/tre/documentation/regex-syntax/) regular expression.
