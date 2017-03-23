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
 - Crear dir
 - git add .
 - git commit -m "BFD0"
 - git push origin bugFixDos

### Mas commits a BFD
 - Editar Readme
 - git add .
 - git commit -m "BFD1"
 - git push origin bugFixDos



### Mas commits a la rama
 - git checkout bugFix
 - Editar Readme
 - git add .
 - git commit -m "BF2"
 - git push origin bugFix



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



### Merge bugFixDos en bugFix
 - git checkout bugFixDos
 - Edit Readme
 - git add .
 - git commit -m "BFD3 - Merge BF"
 - git merge bugFix



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



### Rebase bugFixDos en bugFix
 - git checkout bugFixDos
 - Edit Readme
 - git add .
 - git commit -m "BFD4 - Merge BF"
 - git rebase bugFix
 - Resolver conflictos conforme se apliquen los commits (git add . && git rebase --continue)
 - Si ocurre un error: git rebase --abort
 - Si quieres omitir un commit: git rebase --skip



### Update bugFix
 - git checkout bugFix
 - git rebase bugFixDos
 - git push origin bugFix
 - Esto mostrará de manera linear los cambios de bugFixDos en bugFix



### Merge bugFix en bugFixDos
 - git checkout bugFixDos
 - git merge bugFix
 - Update readme
 - git add .
 - git commit -m "BFD5 - git merge bugFix"
 - git push origin bugFixDos


### Merge bugFixDos en bugFix
 - git checkout bugFix
 - git merge bugFixDos
 - Update readme
 - git add .
 - git commit -m "BF5 - git merge bugFixDos"
 - git push origin bugFix

