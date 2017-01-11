## stream.sh

`stream.sh` adds various stream operators to shell.

**Lambda expressions are expressed with `§0`, `§1` ... as its arguments. (type it with Option+6 on a Mac!)**
`§0` can be shortened to `§`.

```sh
ls | foreach cp § dest/§
ls | map "file: §"
seq 1 10 | filter [ § -gt 5 ]
```

