# ISW_TP1_SGC_ACVLG
Trabajo practico numero 1 ingenieria del software

#Este es el cambio que hizo Agus jeje

#Este es el cambio que hizo Bruno

#Este es el cambio que hizo Pablo jeje x2

#Este es el cambio que hizo Santi

--------------------------------------------------------------
Respuestas:

2b) Para ignorar determinadas rutas, archivos y/o extensiones, lo que debemos hacer es crear un archivo llamado .gitignore, dentro de este mismo es donde se define que ignorar.

2g) Siguiendo la metodología propuesta por Gitflow, para llevar el Release1 al main/master(entorno productivo), primero esta misma debería tener como origen al branch develop (rama destinada exclusivamente al desarrollo y al añadido de features). Release se utiliza para revisar y pulir el código a ponerse en producción, y una vez se logra una conformidad con los cambios a introducir, se debe fusionar el branch con la rama main y etiquetar con un número de versión (también se debería fusionar con la rama develop para evitar inconsistencias).

2k) Para esto, siguiendo el modelo de GitFlow debemos hacer desde develop una nueva release (release 3), y luego desde la rama principal (master) debemos hacer un pull request a esta y por último el merge.

3) 
a) Para documentar en git contamos con varias herramientas, los clásicos comentarios en el código, los mensajes seteados en los distintos commits, los comentarios a la hora de hacer merges y pull request, el versionado, y por último y como herramienta a destacar tenemos el archivo README.md que se encuentra en la carpeta principal del repositorio en Github. El mismo, debería ser utilizado para documentar cada nueva feature introducida en cada commit + push realizado. Por ejemplo: un desarrollador trabaja en incorporar un ABM de vendedores, al finalizar, podría agregar en el README toda la información relevante asociada a estas nuevas características.
Esta misma respuesta podría considerarse una nueva versión del README y sirve como ejemplo.

b) Un pull request nos permite comparar dos ramas con la intención de mergearlas. La persona que busca realizar esta acción, debería indicar de manera precisa los motivos (el por qué de los cambios) por los cuales desea fusionar las ramas, ya sea porque corrigió ciertos errores, agregó nuevas características o simplemente pulió detalles del código. Github permite documentar estos motivantes y además establecer criterios de seguridad, por ejemplo, cantidad de aprobaciones para aceptar un PR, establecer permisos, y una gran cantidad de funcionalidades más.




