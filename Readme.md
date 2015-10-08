https://blog.filippo.io/building-python-modules-with-go-1-5/

```
$ go build -buildmode=c-shared -o foo.so
$ python3 -c 'import foo; print(foo.sum(2, 40))'
```
