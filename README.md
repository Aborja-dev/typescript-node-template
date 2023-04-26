1: configurar typescript
    librerias instaladas:     
        "ts-node-dev": "^2.0.0",
        "typescript": "^5.0.4"
    scripts en package json:
        "tsc": "tsc",
        "start": "tsc && node build/index.js",
        "dev": "ts-node-dev src/index.ts",
    correr npm run tsc -- --init, colocar el outDir en ./build, activar las opciones noImplicitAny noUnusedParameters 
2 configurar jest
        librerias instaladas:     
    "@jest/types": "29.5.0",
    "@types/jest": "^29.5.1",
    "@types/node": "18.16.1",
    "jest": "29.5.0",
    "ts-jest": "29.1.0"
    scripts en package json:
        "test": "jest",
        "test:watch": "jest --watchAll --verbose",
        "test:coverge": "jest --collectCoverage"
    crear el archivo jest.config.ts
