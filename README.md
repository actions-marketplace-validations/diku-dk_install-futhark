# Install Futhark compiler

This action installs the Futhark compiler in a Linux-based GitHub
Actions runner.  The compiler is installed in `$HOME/.local`, which
means it will be on the `$PATH` of a standard setup.

## Inputs

`version`

The version to install (e.g. `0.22.3`), or the string `'latest'`.

## Example usages

```
      - uses: diku-dk/install-futhark@v1
        with:
          version: '0.22.3'
```

```
      - uses: diku-dk/install-futhark@v1
```

```
      - uses: diku-dk/install-futhark@v1
        with:
          version: 'latest'
```
