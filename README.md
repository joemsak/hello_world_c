# Hello, World in C

### Learning C, why not 🤷🏼‍♂️

## Install
```
git clone git@github.com:joemsak/hello_world_c.git
cd hello_world_c
gcc src/hello.c -o bin/hello
```

## Build (optional)
```
gcc src/hello.c -c -o build/hello.o
ld build/hello.o -o bin/hello -l System -syslibroot `xcrun -sdk macosx --show-sdk-path` -e _main -arch arm64
```


## Run
```
./bin/hello
```
