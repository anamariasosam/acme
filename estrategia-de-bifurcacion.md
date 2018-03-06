# Estrategia de bifurcación

---



| **Ramas** | **Descripción** |
| :--- | :--- |
| master | Cualquier commit que esté en esta rama debe estar preparado para subir a producción |
| develop | Está el código que conformará la siguiente versión planificada del proyecto |
| feature | Estas ramas se utilizan para desarrollar nuevas características de la aplicación que, una vez terminadas, se incorporan a la rama developSe originan a partir de la rama developSe incorporan siempre a la rama develop |
| release | Estas ramas se utilizan para preparar el siguiente código en producción. En estas ramas se hacen los últimos ajustes y se corrigen los últimos bugs antes de pasar el código a producción incorporándolo a la rama masterSe originan a partir de la rama developSe incorporan a master y develop |
| hotfix | Esas ramas se utilizan para corregir errores y bugs en el código en producciónSe origina a partir de la rama masterSe incorporan a la master y develop |



