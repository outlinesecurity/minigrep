# minigrep

A small command line program to search a file for a query. 

## Examples

* Case sensitive
```
./target/debug/minigrep project sample.txt
```
* Cases insensitive
```
export IGNORE_CASE=true
./target/debug/minigrep PROJECT sample.txt
```