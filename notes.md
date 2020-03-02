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

- screen resolution and viewport
  
  - viewport meta tag
  - media query(@media rule)
  - bootstrap has done the hard work
  - learn to use the bootstrap classes that use the breakpoints

- bootstrap grid
  - mobile-first
  - based on CSS flexbox
  - [example.html](example.html) always need the following for a bootstrap grid:

```html
    <div class="container">
        <div class="row">
            <div class="col">
                Content
            </div>
    </div>
```
- try container-fluid
- each row can have up to twelve columns 