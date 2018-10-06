# some useful shell commands

### grep 
search and filter file content

```fish
grep -v "//" file.js
# invert matching for "//" in file.js and print out the result
```

```fish
find . -name "*.js" | grep -i long | grep -v node_modules
# 1. find all .js files
# 2. that have word 'long' in their file/path string (-i case insensitive) 
# 3. that does not have word 'node_modules'
```

