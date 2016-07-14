# nullarbor-spades-fast
Runs nullarbor using spades-fast for assemblies

##Author

Jason Kwong (@kwongjc)

##Dependencies
* Python 2.7.x
* [Nullarbor](https://github.com/tseemann/nullarbor)
* [mdu-tools](https://github.com/MDU-PHL/mdu-tools) (includes spades-fast)

##Usage

```
$ nullarbor-spades-fast.py -h
usage: 
  nullarbor-spades-fast.py DIRECTORY

Alters Nullarbor makefile to run spades-fast
1. Generate the Nullarbor makefile using "nullarbor.pl"
2. Run this script as specified above
3. Run the makefile eg. "nice make -j 8 -C /home/user/nullarbor" or enter the nullarbor output directory and type "make"

positional arguments:
  DIRECTORY   Nullarbor output directory containing Makefile (required)

optional arguments:
  -h, --help  show this help message and exit
```

##Bugs

Please submit via the [GitHub issues page](https://github.com/kwongj/nullarbor-spades-fast/issues).  

##Software Licence

[GPLv3](https://github.com/kwongj/nullarbor-spades-fast/blob/master/LICENSE)
