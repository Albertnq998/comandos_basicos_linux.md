# ALBERT NINA
## Comando basico de linux
### Permite ver la version de redhat linux
```bash
cat /etc/redhat-release
```
pwd: te demuestra la ruta actual donde estas ubicado 
```bash 
pwd
```
cd: sirve para cambiar de directorio(Cambiar entre carpeta)
``` bash 
cd ~ # cambiar a la carpeta del usuario.
cd /  # cambia a la carpeta raiz.
cd .. # salir de una carpeta.
cd nombre_carpeta # cambiar una carpeta especifica. (ingresar a una carpeta).
```
### ls: Mostrar archivo y carpeta.
```bash 
ls    # muestra las listas de archivos y carpeta 
ls -l # Muestra una lista detallada.
ls -a # Muestra una lista incluido archivo ocultos.
```
## Crear archivos y carpetas.
```bash
touch archivo.java # crea un archivo.
mkdir carpeta # crea una carpeta.
```
## Copiar archivos y carpetas
```bash
cp archico-copiar.txt archivo-copia2.txt #copiar un archico
cp -r carpeta-1 carpeta-2 #copiar una carpeta
```
### Mover y Renombrar archicos y carpetas
``` bash 
mv archico.txt ../carpeta-1 #mover un archico.
mv carpeta-2 carpeta-3 #mover una carpeta.

mv archico-viejo.py archico-nuevo.py #cambiand el nombre
mv carpeta-vieja carpeta-nueva cambiar el nombre de la carpeta
```
### Eliminar archivos y carpetas 
``` bash 
rm archivo.txt # eliminar una archivo
rm -r carpeta #eliminar una carpeta.
rm -l archivo.txt #
```
## Administracion de usuario y grupo

### Administrar usuario
``` bash
useradd a- senati #sirve para crear un usuario.
userdel senati #sirve para eliminar un usuario.

passed senati -1 nuevo_usuario usuario_anterior #cambia el nombre del usuario.
usermod -aG grupo usuario #asigna un usuario a un grupo.
```
### Administrar grupos
``` bash
groupadd nombre_grupo #crear grupo.

su  usuario # cambiar usuario 
exit #salir de usuario actual.
```
## permisos en archico y carpeta 
### Administra usiario y grupos 
 ```bash 
groups usuario # saber si un usiario pertenece a un grupo.
```
### Permisos a carpetas o directorios 
``` bash 
chmod 700 #asigna permisos a una carpeta.
chmod rwx------ carpera # asigna permisos con letras a una carpeta.
```
### Permisos a archivos.
```bash 
chmod 700 #asigna permisos a una carpeta.
chmod rwx------ carpera # asigna permisos con letras a un archivo.
```
### Ver y manipular archivos 
```bash
vi archivo.extension # para editar un archivo
i # insertar texto.
Esc + :wq # Guardar y Salir
Esc + :q! # Salir sin guardar cambios
cat archivo.extension #solo para ver contenido del archivo.
```

### Agregar carpeta a un grupo 
```bash
chgrp grupo carpeta/ # Sirve para agregar una carpeta a un grupo
```
### Agregar usuario a un grupo
```bash
usermod -aG grupo usuario # Agregar usuario a un grupo
```

