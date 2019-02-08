> Tomado de 
>
> [Digital Ocean](https://blog.digitalocean.com/how-to-conduct-effective-code-reviews/)

Aquí se encuentra el Post completo [How to Conduct Effective Code Reviews](https://blog.digitalocean.com/how-to-conduct-effective-code-reviews/)(Ingles).

# Introducción

El proposito de un Code Review es asegurarnos de que todas las partes involucradas en la creación, edición y testeo de código fuente puedan mantener una conversación entre ellos sobre nuevos cambios agregados a un proyecto esto para mantener y cumplir los siguientes puntos:



-   Seguridad
-   Estilos de Codificación
-   Standares
-   Evitar incluir bugs 
-   Aprender del equipo sus fortalezas y debilidades

En cada revision de código deben estar por lo menos dos personas involucradas El developer que quiere agregar cambios al código (**Submitter**) y otro miembro del equipo con un mayor conocimiento sobre el código (**Reviewer**).



**Nota**: Con cada nuevo Code Review se debe hacer un checklist de los puntos antes mencionados para saber si los cambios cumplen con lo establecido.



**Nota**: Es recomendable que también se encuentre el dueño del feature, es decir, el dueño del archivo inicial ya que él estableció las bases del mismo.

# Submissions: Que incluir en un Code Review

Un Code Review inicia regularmente con un contribuidor enviando cambios al proyecto y la descripción de estos cambios deberán de contener lo siguiente:

-   Una clara **descripción** acerca de los cambios enviados y un resumen general del por qué estos cambios son necesarios.
-   El **alcance** del cambio.
-   Areas donde el Reviewer debe poner **atención**.
-   **Dudas** que requieran **aclaración**.
-   Y cualquier otro detalle que ayude a los Reviewers a **entender** el por qué del **cambio**.

La comunicación escrita de cosas técnicas puede ser algunas veces difícil: 

-   Las personas tienen tiempo limitado
-   Cada persona tiene un tarea/desafio en cada momento

Por eso se establecen los roles que se juegan en el proceso de un Code Review:

-   Como un escritor, Se tan claro como debas de serlo. Cuando tengas dudas se descriptivo.
-   Como un lector, Realiza preguntas cuando algo no este claro.
-   Como un crítico, Se amable cuando alguien suba cambios.
-   Como el presentador, No te preocupes ni te angusties cuando tus cambios no sean revisados en el momento deseado o cuando sean rechazados por no cumplir con alguno de los puntos mencionados en la Introducción.
