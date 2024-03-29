# Google Summer of Code 2015

<img src="/blog/images/gsoc2015.jpg" alt="" style="width: 200px;"/>

I was selected by GSoC 2015.

## Proposal

My proposal is: [John the Ripper jumbo robustness improvements](http://www.google-melange.com/gsoc/proposal/public/google/gsoc2015/zhaokai/5629499534213120)

### Abstract

This project aims at improving the robustness of John the Ripper jumbo,
especially faced with invalid input. There are mainly two approaches, 
one through fuzzing, and the other through source code review. By fuzzing,
American Fuzzy Lop(AFL) can be customized and integrated with John the Ripper
jumbo. By source code review, manual reviews and automated static analysis 
such as valgrind, cppcheck and ClangStatic Analyzer can be used.
