Investigación: Git y GitHub
SIS-414 G-2  
Estudiante: Pedro Serrudo Llanos

1. ¿Qué es una rama (branch) en Git y para qué se utiliza?
Una rama es como una línea paralela de trabajo dentro de un proyecto. Se utiliza para desarrollar nuevas características, corregir errores o probar ideas sin afectar el código principal (generalmente la rama `main` o `master`). Así puedo trabajar de forma aislada y luego unir mis cambios.

2. Explica con tus palabras qué significa hacer un merge.
Hacer un merge es combinar los cambios de una rama con otra. Por ejemplo, si creo la rama `nueva-funcionalidad` y después quiero llevar esos cambios a `main`, hago un merge para unir ambas versiones del proyecto.

3. ¿Qué es un conflicto de fusión (merge conflict) y cómo se puede resolver?
Un conflicto de fusión ocurre cuando dos ramas modifican la misma parte de un archivo de manera distinta y Git no sabe cuál de las versiones mantener.  
Para resolverlo, yo debo abrir el archivo, decidir qué cambios conservar (los míos, los del otro, o una mezcla de ambos) y luego guardar y hacer un commit para completar la fusión.

4. Diferencia entre fork y clone en GitHub.
- **Clone**: Es cuando descargo un repositorio desde GitHub a mi computadora para trabajar en él localmente.  
- **Fork**: Es cuando hago una copia del repositorio en mi propia cuenta de GitHub. Con el fork puedo proponer cambios al proyecto original mediante pull requests.

5. ¿Qué es un pull request y para qué se usa en proyectos colaborativos?
Un pull request (PR) es una solicitud para que los cambios que hice en mi repositorio o en mi rama sean revisados e integrados en el repositorio principal. Se usa en proyectos colaborativos porque permite que el equipo revise, comente y apruebe los cambios antes de unirlos al código principal.

6. Tres buenas prácticas para colaborar en equipo usando GitHub
   1. **Crear ramas específicas para cada tarea**: No trabajar directamente en `main`, sino en ramas separadas para mantener ordenado el proyecto.  
   2. **Escribir mensajes de commit claros y descriptivos**: Así todos entienden qué cambios se hicieron.  
   3. **Usar pull requests con revisiones**: Antes de hacer un merge, pedir revisión a los compañeros para asegurar calidad y evitar errores en el código principal.
