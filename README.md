<h3>TODO EL CODIGO ES DE MI AUTORIA. TIENEN TOTAL LIBERTAD PARA MIRAR MI REPOSITORIO:https://github.com/movix86/</h3>
La prueba se realizo conforme al requerimiento de la prueba. <br>
-Aqui hay otra rama de este proyecto. Pero preferi enviarles la actual. https://github.com/movix86/konecta
<br>
Por favor Antes de comenzar debe verificar si tiene instalado Composer! <br>
Importante tener Xampp o Wamp y crear una base de datos llamada: laravel y ejecutar las migraciones de laravel <br>
Debe seguir las siguientes instrucciones:
- Abrir powershell o Gitbash.
- Clonar el repositorio con: git clone git@github.com:movix86/konecta-prueba.git store
- Ubicarse sobre el proyecto clonado con los comandos en consola; cd store
- Luego installar composer: composer install
- En la raiz del proyecto hay un archivo llamado: .env-example, dele clic derecho y cambiar nombre y renombre el archivo; .env
- Abra el archivo .env y en la linea 13 verifique que la base de datos se llame; DB_DATABASE=laravel
- Despues ejecutar el siguiente comando en la consola; php artisan migrate
- Luego ejecutar el siguiente la siguiente linea; php artisan key:generate
- Ahora escriba en la consola este comando y ejecutelo; php artisan serve
- La url que le aparece en la consola de comando copiela y peguela en su navegador
- Por ultimo ejecute el comando; php artisan optimize
- LISTO ya debe ver en funcionamiento la tabla y crear usuarios, este pequeño desarrollo es un  paquete y lo tiene todo.
<br>

<h3>Base de Datos:</h3>
<p>Para la base de datos se utilizo un ORM llamado Eloquent, es una herramienta de Laravel y sirve para mapear la BD.</p>
<br>

<h3>Javascript:</h3>
<p>Se utiliza en el front y en este caso se uso para que cuando el usuario vaya a eliminar a un producto, arroje una ventada modal de advertencia,</p>
<p>ademas el modal es solo 1, no se repite codigo. con JS se puede hacer que por medio de rutas se elimine los empleado y generar los modales sin repetir codigo.</p>

<br>


