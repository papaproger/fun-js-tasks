# Fun JS Tasks

### <a id="0">Contents</a>

- [Task #1](#1)
- [Task #2](#2)

### <a id="1">Task #1</a>

```javascript
const a = [1, 2, 3]

const b = {
    0: 1,
    1: 2,
    2: 3,
}

const index = {
    valueOf() {
        return "1"
    },
    toString() {
        return 2
    },
}

//console.log(`${a[index]} ${b[index]}`)
```

<a href="#0"><img src="https://img.shields.io/badge/go%20to%20contents%20&#9650;-242424?style=for-the-badge" alt="go to Contents" /></a>

### <a id="2">Task #2</a>

```javascript
const a = {
    [Symbol.toPrimitive](hint) {
        return hint == "default" ? 1 : "2"
    }
}

//console.log(++a)
```

<a href="#0"><img src="https://img.shields.io/badge/go%20to%20contents%20&#9650;-242424?style=for-the-badge" alt="go to Contents" /></a>

### by

[PapaProger](https://github.com/papaproger)