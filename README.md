# mkl-discover
Python module to check if libmkl_rt.so is installed.

# How it works

Checks if $MKLROOT is set and can be found

Checks if libmkl_rt.so can be found somewhere below $MKLROOT

Checks if the path where libmkl_rt.so is installed is within $LD_LIBRARY_PATH
