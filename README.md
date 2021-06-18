# nodejs-rest-example
## Instalación

```
    mkdir myapp
    cd myapp
    npm init
    npm install express --save
```

#### Crear  Archivo app.js
```
touch app.js
```
Agregar al archivo **app.js**
```
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`)
})
```
