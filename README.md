# Documentación Bot Bumer Solutions
Desarrollado por:

```
Paolo Lizarraga y Daniel Loja
```

A continuación se describirán los pasos necesarios para la instalación y puesta en marcha del chatbot de Bumer Solutions en Telegram. De igual forma, se explicará a detalle el código empleado.

# Preparación del proyecto

Para instalar las dependencias, escribir en una terminal:

```
npm install
```

### Ejecutar el proyecto

```
npm run start
```

### Estructura del proyecto

```
$ tree
.
├── chatbot
│   ├── helpers
|	|	├── structFunctions.js
│   ├── Telegram
|	└──	├── telegramBot.js
├── db
│   ├── data
|	|	├── dataDePrueba.js
│   ├── Auditorias.js
│   ├── Cuestionarios.js
│   ├── Detalle_auditorias.js
│   ├── index.js
│   ├── Preguntas.js
│   └── Respuestas.js
├── config.js
├── server.js
└── README.md
```