To reproduce a bug involving spack and axios:

```
npm i
npx spack
```

You should get the output:

```
$ npx spack
error: Expected ';', '}' or <eof>
 --> /home/tom/mycode/swc-test/node_modules/axios/package.json:2:10
  |
2 |   "_from": "axios",
  |          ^
  |
note: This is the expression part of an expression statement
 --> /home/tom/mycode/swc-test/node_modules/axios/package.json:2:3
  |
2 |   "_from": "axios",
  |   ^^^^^^^
```
