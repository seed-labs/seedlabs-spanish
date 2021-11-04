# TODO

## 11/04/2021:

The English version is modified. The following note is added
to the end of Task 2

```
\paragraph{Note.} You should use the \texttt{-m32} flag when
compiling the above program, so the binary code \texttt{prtenv}
will be for 32-bit machines,
instead of for 64-bit ones. The vulnerable program \texttt{retlib} is
a 32-bit binary, so if \texttt{prtenv} is 64-bit, the address of the
environment variable will be different.
```
