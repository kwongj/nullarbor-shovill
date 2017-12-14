# nullarbor-shovill
Runs Nullarbor using Shovill for assemblies

##Author

Jason Kwong (@kwongjc)

##Dependencies
* Python 2.7.x
* [Nullarbor](https://github.com/tseemann/nullarbor)
* [Shovill](https://github.com/tseemann/shovill)

##Usage

```
$ nullarbor-shovill.py -h
usage: 
  nullarbor-shovill.py DIRECTORY

Alters Nullarbor makefile to run shovill
1. Generate the Nullarbor makefile using "nullarbor.pl"
2. Run this script as specified above
3. Run the makefile eg. "nice make -j 8 -C /home/user/nullarbor" or enter the nullarbor output directory and type "make"

positional arguments:
  DIRECTORY           Nullarbor output directory containing Makefile (required)

optional arguments:
  -h, --help          show this help message and exit
  --assdir DIRECTORY  directory containing previous assemblies (default="/mnt/seq/MDU/QC/")
```

##Bugs

Please submit via the [GitHub issues page](https://github.com/kwongj/nullarbor-shovill/issues).  

##Software Licence

[GPLv3](https://github.com/kwongj/nullarbor-shovill/blob/master/LICENSE)
