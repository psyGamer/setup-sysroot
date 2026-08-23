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

| ID                          | Name                 | Kernel     | C Library  |
|-----------------------------|----------------------|------------|------------|
| `x86_64-debian13-linux-gnu` | Debian 13 "Trixie"   | Linux 6.12 | glibc 2.41 |
| `x86_64-debian12-linux-gnu` | Debian 12 "Bookworm" | Linux 6.1  | glibc 2.36 |
| `x86_64-debian11-linux-gnu` | Debian 11 "Bullseye" | Linux 5.10 | glibc 2.31 |
| `x86_64-debian10-linux-gnu` | Debian 10 "Buster"   | Linux 4.19 | glibc 2.28 |
