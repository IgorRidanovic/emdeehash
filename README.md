# Meta Fide Emdeehash
Fast md5 hash generator for multiple files. It creates sidecar .md5 files containing md5 hashes for arbitrary number of files supplied as command line arguments. It also keeps track of all generated hashes in a log file.

It processes files in parallel, but it's not optimized for the case where the number of input files exceeds the number of available cores. Experiment with the file read chunk size to determine optimal size for the input file size.

https://www.metafide.com

Usage:

emdeehash SomeFile1 SomeFile2 SomeFile3...
