# Developer and advanced user notes

For those wishing to specify custom compiler flags, for example "-march=native", set environment variable
[FFLAGS](https://mesonbuild.com/Reference-tables.html#compiler-and-linker-flag-environment-variables)
so that the meson-python build system passes them to the compiler.
 For example:

```bash
FFLAGS="-march=native" python -m pip install -e ./glowpython2
```
