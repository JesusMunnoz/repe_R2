
Repeticion Reto 2

Creamos repo en local en carpeta REPOSITORIOS
cmd git init nombre_nuevo_repositorio, en nuestro caso "repe_R2"
repe de repetir

<<<<< reto 2.7 >>>>>
Hemos subido el archivo al “stage”, pero ahora nos damos cuenta que no es el archivo correcto y queremos sacarlo del “stage”. (Es decir dar marcha atrás al git add).

- Haremos un "git add ." seguido de "git reset HEAD"
vamos de "staging area" al "working directory" que es el paso previo a "git add .", como si no hubiesemos hecho git add .

<<<<< reto 3 >>>>>
subir archivo al "stage" >>> git add .
Comprobar estado >>> git status
Hacer commit >>> git commit -m "Haz el commit de este archivo"
Comprobar estado >>> git status
Revertir commit >>> git reset --soft HEAD~ 
así volvemos a zona en la quye hay que introducir de nuevo el commit

<<<<< reto 4 >>>>>
- metemos en la carpeta "reto 2" archivo ".gitignore"
- este va a ignorar las imágenes de esa carpeta, así no pesará tanto, ya que le hemos dicho que ignore los .PNG. 
Los .PNG que se encuentran fuera de la carpeta "reto 2", nolos ignorará.

Lo quer habría que hacer en proyectos grandes en los que compañeros han instalado como por ejemplo librerías sería:
- git pull
- git init