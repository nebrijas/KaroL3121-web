# ACTIVIDAD DIRIGIDA 2
### PRACTICANDO EN GIT BASH Y ORDENANDO LAS CARPETAS DE TRABAJO

En esta actividad se detallan los pasos realizados para pasar el reportaje de datos expuesto en el README.md a ad1.md. Con esta acción el README.md quedó como un índice. Para completar la actividad tuve que seguir minuciosamente la clase.

#### Pasos realizados:
1. Ingresé a mi repositorio en GitHub [KaroL3121-web](https://github.com/nebrijas/KaroL3121-web) y luego accedí a la opción pages con el objetivo de hacer las configuraciones de main y root. Estos pasos ayudan a garantizar que el directorio también se pueda visualizar en HTML.
2. Generé desde mi repositorio en GibHub un nuevo archivo, que denominé ad2.md.
3. Accedí a la terminal de GitBash, donde probé una serie de comandos, el primero de ellos `pwd`. Todas estas acciones se ejecutan con `enter`.
4. El siguiente paso fue clonar mi repositorio a través de `git clone https://github.com/nebrijas/KaroL3121-web` para que estuviera a nivel del directorio local del ordenador. Cuando lo hice  me indicaba que la ruta KaroL3121-web ya existía y no era un directorio vacío. Pasé varias horas intentando saber la razón. Luego entendí que era porque durante la última clase  había clonado y la carpeta ya estaba en el ordenador. 
5. Una vez solventado el tema de la clonación, hice un `ls` para comprobar que estuviera en mi directorio.
6. Después ejecuté un `cd` más el nombre de mi repositorio para acceder.
7. Luego di  `git config user.name` más KaroL3121, que es mi usuario de GitHub.
8. La siguiente acción fue dar `git config user.email karol0631@gmail.com`
9. Regresé al navegador para obtener el token desde mi cuenta de GitHub [https://github.com/settings/tokens](https://github.com/settings/tokens). En las configuraciones de expiración seleccioné 60 días y en select scopes eligí Repo. Luego copié el extenso código.
10. Volví a la terminal de GitBash y accioné `echo "(más el token)"> ../.token`, lo que me brindó un archivo en la parte superior del directorio, para que no estuviera en el mismo nivel de git. Comprobé que estuviera a través de `ls ../.token`.
11. Edité luego mis archivos a través de `nano.exe.` En este caso el ad2.md que ya había creado y le cambié el título y descripción.
12. Posteriormente, con un `git status`, comprobé que se habían hecho cambios.
13. Con `git add` añadí los cambios realizados.
14. Escribí `git commit -m "creo carpeta de trabajo dos"` para que se reflejara el comentario sobre lo que estoy haciendo en el archivo.
15. Coloqué después `git push` para publicar los cambios locales en el repositorio digital. Para ejecutarlo debí escribir mi usuario y token. Accedí a la web y los cambios ya se reflejaban.
16. Repetí el procedimiento, a partir nano (desde el punto 11 al 15), para crear el archivo ad1.md y copiar el reportaje de datos que estaban en el README.md. Y ya  mi repositorio con las actividades en sus propios archivos numerados estaba listo.






