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
Ejecutar
```
node app.js
```

## Llamadas
Para llamar al servicio de Hello World debes invocar.
```
http://localhost:4000/
```
Para llamar al servicio que responde el JSON de Hello World debes invocar;
```
http://localhost:4000/json
```

