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