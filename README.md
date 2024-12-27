# NickelbackFS_4x_ncnn

NickelbackFS_4x converted to bin/param for NCNN with Chainner

### Example usage with `upscayl-bin`

```c
$ git clone https://github.com/anonyco/NickelbackFS_4x_ncnn.git
$ wget -O Lenna512x512.png "https://upload.wikimedia.org/wikipedia/en/7/7d/Lenna_%28test_image%29.png"
$ upscayl-bin -s 4 -n NickelbackFS_4x -m NickelbackFS_4x_ncnn/models -i Lenna512x512.png -o Lenna2048x2048.png
```

### Credit/License

Credit goes to BlackScout's upload [https://openmodeldb.info/models/4x-NickelbackFS](https://openmodeldb.info/models/4x-NickelbackFS), from which we are under the terms of the GPL-3.0-only.


