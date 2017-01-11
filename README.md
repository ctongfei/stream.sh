## stream.sh

`stream.sh` adds various stream operators to shell.

**Lambda expressions are expressed with <0>, <1> ... as its arguments.**

```sh
ls | foreach cp "<0>" "dest/<0>"
ls | map "file: <0>"
```
