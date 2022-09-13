# [`rm`](https://github.com/ginokent/rm)

`rm` (meaning: **_remain_**) behaves like [GNU coreutils `rm`](https://www.gnu.org/software/coreutils/manual/html_node/rm-invocation.html) but **_remain_** files or directories in `~/.Trash`.  


## HOW TO INSTALL

```bash
(install() { curl --tlsv1.2 -LRSs https://raw.githubusercontent.com/ginokent/rm/HEAD/rm -o "$1" && chmod +x "$1"; } && install /path/to/bin/rm)
```
