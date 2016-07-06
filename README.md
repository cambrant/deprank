deprank 0.1

deprank is a Unix library dependency ranker for DNF/Yum based systems. It ranks
system packages based on how many binaries on the system which use them. For
example, the DNF package libpng-2 is used by by 195 executables on my system,
which says something about the necessity of that package, and the importance
that the code in that package works properly.

Dependencies:
natsort (Available on PyPI)
