# TinyFileDialogs
[Vareille's](https://sourceforge.net/u/vareille) Cross-Platform [TinyFileDialog](https://sourceforge.net/projects/tinyfiledialogs/) Library

---

### Compiling

1. Include [`src/tinyfiledialogs.h`](src/tinyfiledialogs.h) in your code to get function declaration & other definitions.
2. To compile the [`src/tinyfiledialogs.c`](src/tinyfiledialogs.c) & on windows make sure to link with the following flags:

```bash
-lcomdlg32 -lole32 -luser32 -lshell32
```

Example:

- Linux/Darwin: `clang main.c src/tinyfiledialogs.c`
- Windows: `clang -lcomdlg32 -lole32 -luser32 -lshell32 main.c src/tinyfiledialogs.c`

---

## Thanks
