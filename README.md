# setup-sysroot

Setup a precompiled sysroot for cross-compiling or targeting alternative C libraries.

Feel free to contribute missing toolchains.

## Usage

```yaml
- uses: psyGamer/setup-sysroot@v1
  with:
    # ID of the desired toolchain.
    # Refer to the support table below for a list of all supported toolchains.
    # Required.
    toolchain:
```

## Support Table

|                          ID |               Name | Architecture |     Kernel |  C Library | C Compiler |
|-----------------------------|--------------------|--------------|------------|------------|------------|
| `x86_64-debian10-linux-gnu` | Debian 10 "Buster" |       x86_64 | Linux 4.19 | glibc 2.28 |      GCC 7 |
