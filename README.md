Inicio del README
=================

### En master
 - Editar README
 - git add .
 - git commit -m "First commit"
 - git push oirigin master

### En master
 - Fix README
 - git add .
 - git commit -m "M0"
 - git push origin master

### En master
 - Fix README
 - git add .
 - git commit -m "M1"
 - git push origin master

### Actualizar Master
 - git checkout master
 - Editar Readme
 - git add .
 - git commit -m "M2"
 - git push origin master



### Nueva rama
 - git checkout -b bugFixTres
 - Editar Readme
 - git add .
 - git commit -m "BFT0"
 - git push origin bugFixTres

### Mas commits a BFT
 - Editar Readme
 - git add .
 - git commit -m "BFT1"
 - git push origin bugFixTres



### Mas commits para Master
 - git checkout master
 - Editar Readme
 - git add .
 - git commit -m "M3"
 - git push origin master

### Mas commits para Master
 - Editar Readme
 - git add .
 - git commit -m "M4"
 - git push origin master


### Rebase bugFixTres en master
 - git checkout bugFixTres
 - Edit Readme
 - git add .
 - git commit -m "BFT2 - rebase - Master"
 - git rebase master
 - Resolver conflictos (git add . && git rebase --continue)
 - Omitir con git rebase --skip
 - Cancelar con git rebase --abort
