Inicio del README
=================

### Primer commit
 - Crear README
 - git add .
 - git commit -m "First commit"
 - git push oirigin master

### Corregir readme
 - Editar README
 - git add .
 - git commit -m "M0"
 - git push origin master

### Corregir estilos
 - Editar README
 - git add .
 - git commit -m "M1"
 - git push origin master




### Nueva rama
 - git checkout -b bugFix
 - Editar Readme
 - git add .
 - git commit -m "BF0"
 - git push origin bugFix

### Mas commits a la rama
 - Editar Readme
 - Crear file
 - git add .
 - git commit -m "BF1"
 - git push origin bugFix



### Nueva rama
 - git checkout -b bugFixDos
 - Editar Readme
 - Crear file
 - git add .
 - git commit -m "BFD0"
 - git push origin bugFixDos


### Mas commits a BFD
 - Editar Readme
 - git add .
 - git commit -m "BF2"
 - git push origin bugFix

### Mas commits a la rama luego de merge
 - git checkout bugFix
 - Editar Readme
 - git add .
 - git commit -m "BF3"
 - git push origin bugFix

### Mas commits a la rama BF
 - Editar Readme
 - git add .
 - git commit -m "BF4"
 - git push origin bugFix




### Nueva rama
 - git checkout -b bugFixDos
 - Editar Readme
 - Crear dir
 - git add .
 - git commit -m "BFD0"
 - git push origin bugFixDos

### Mas commits a BFD
 - Editar Readme
 - git add .
 - git commit -m "BFD1"
 - git push origin bugFixDos

### Mas commits a BFD
 - git checkout bugFixDos
 - Editar Readme
 - git add .
 - git commit -m "BFD2"
 - git push origin bugFixDos

### Corregit BFD
 - Fix Readme
 - git add .
 - git commit -m "BFD3"
 - git push origin bugFixDos




### Actualizar Master
 - git checkout master
 - Editar Readme
 - git add .
 - git commit -m "M2"
 - git push origin master


### Merge bugFixDos en bugFix
 - git checkout bugFixDos
 - Edit Readme
 - git add .
 - git commit -m "BFD3 - Merge BF"
 - git merge bugFix




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


### Rebase bugFixDos en bugFix
 - git checkout bugFixDos
 - Edit Readme
 - git add .
 - git commit -m "BFD4 - Merge BF"
 - git rebase bugFix
 - Resolver conflictos conforme se apliquen los commits (git add . && git rebase --continue)
 - Si ocurre un error: git rebase --abort
 - Si quieres omitir un commit: git rebase --skip



### Actualizar rebase en master
 - git checkout master
 - git rebase bugFixTres
 - git push origin master
