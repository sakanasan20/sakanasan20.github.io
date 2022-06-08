---
title: Module System
weight: 210
menu:
  notes:
    name: Module System
    identifier: notes-node.js-module-system
    parent: notes-node.js
    weight: 10
---

<!-- Module System -->
{{< note title="Module System" >}}

```javascript
const fs = require('fs')
const name = require('./utils.js')

fs.writeFileSync('notes.txt', 'hello world!')

console.log('Hi, ' + name)
```
_app.js_

```javascript
console.log('utils.js')

const name = 'Mike'

module.exports = name
```
_utils.js_

{{< /note >}}
