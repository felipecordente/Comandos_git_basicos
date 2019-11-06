alias gitgraph="git log --all --decorate --oneline --graph" -> para poder utilizar gitgraph

git clone <dir navegador>
#por defecto no se nos copiaran las ramas, por tanto la rama que nos interese la tendremos que #subir a mano

git checkout -b feature_1 origin/feature_1 -> con esto seguiremos la rama 

git pull -> actualizaremos todo lo que estemos siguiendo

git pull origin master -> actualizaremos la rama master, o la que nosotros necesitemos

git push <remote> <rama> -> para subir desde mi working area a mi repo grupal una nueva rama

git branch -vv-> me refleja el estado de mis ramas locales y las remotas

##DESPUES DE ACTUALIZAR UN FICHERO
##SIEMPRE EN UNA RAMA QUE NO SEA LA MASTER
git status -> vemos lo que tenemos que actualizar, si esta en rojo git add y luego git commit; y si esta en verde solo hará falta el git commit

git add *

git commit -m ""

git push -> sube tanto la rama como la master, pero como la master NO la hemos tocado, podemos usar este comando

#ahora ya en github tenemos subido los cambios a la rama y lo unico que hay que hacer es pull request y esperar que acepten
