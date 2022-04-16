# mlx-ver_test
test various mlx versions with test cases, choose most appropriate version for our cub3d.

1. Unzip .tgz file you want to test.
2. move mlx_dir to root directory.
3. rename your mlx_dir to mlx.
4. compile and test.

- unzip .tgz command
tar -xvf (filename).tgz

How to compile dylib
1. make dylib.
2. move (filename).dylib in your root directory.
3. compile with flag.

- compile flag
gcc -I. -L. -lmlx -framwork Metal -framwork MetalKit

-L(dir) = directory which your .dylib locate.
-l(lib) = name of your library.