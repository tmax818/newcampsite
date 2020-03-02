- the following is done inside the 2-bootstrap directory:

```bash
$ mkdir newcampsite
$ cd newcampsite
$ code .
```

```bash
$ git init -y
$ npm i bootstrap jquery lite-server popper.js -D
```


- modify [package.json](package.json)
  - add this to the scripts object:

```javascript
    "lite": "lite-server",
    "start": "npm run lite"
```

- create [index.html](index.html)
  - see comments for added scripts

- created a new branch:

```bash
$ git checkout -b 03resWebDes
```