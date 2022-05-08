Linter
Instalar dependencia:
npm install eslint --save-dev

Modificar package.json, agregar debajo de test
"linter": "node ./node_modules/eslint/bin/eslint.js"

Crear configuración en archivo .eslintrc (si se versiona)
npm init @eslint/config

Rules: https://eslint.org/docs/rules/ Airbnb Code Style: https://github.com/airbnb/javascript
