# Comprobador Automático CORE19-03_quiz_cmd

Puede descargar este proyecto en el ordenador local de dos formas:
1. Clonar el  comprobador con el comando `git clone ..`
2. Entrar al  comprobador con el navegador y descargar el fichero del proyecto ZIP con un botón.

El proyecto se descarga, instala y ejecuta en el ordenador local con los siguientes comandos:

```sh
$ ## El .zip del proyecto puede descargarse y descomprimirse.
$ ## O el proyecto también puede copiarse en el ordenador local con:
$ git clone https://github.com/practicas-ging/CORE19-03_quiz_cmd
$
$ cd CORE19-03_quiz_cmd  ## Entrar en el directorio de trabajo del programa de test
$
$ npm install  ## Instala el programa de test, que es un paquete npm
$
$ npm run checks [nombre de la práctica] [nombre_del_usuario]     ## Pasa los tests sobre el repositorio en github
......................................... ## indicando que partes  están correctamente
......................................... ## implementadas y cuales no.
... (resultado de los tests)
$
$ ## Cuando el resultado de los tests locales sea satisfactorio, puede subir su nota al servidor
$ ## para su inclusión en Moodle con el comando:
$ npm run upload
$ 
```

Los tests pueden pasarse tantas veces como sea necesario; incluso con el ejercicio incompleto.
El programa-de-test incluye además un comando para generar el fichero ZIP

```bash
$
$ npm run zip ## Este comando comprime los ficheros a entregar como un fichero xx.zip
$             ## El directorio de trabajo contiene ahora el fichero: CORE19-03_quiz_cmd.zip
```

El fichero `CORE19-03_quiz_cmd.zip` contiene los ficheros de la practica comprimidos y puede subirse a la plataforma para su evaluación.

