# ¿Cuál es la principal diferencia entre un formulario reactivo y un formulario basado en plantillas en Angular?**

A) Los formularios reactivos se definen en el archivo HTML, mientras que los formularios basados en plantillas se definen en el archivo TypeScript.  

B) Los formularios reactivos son más adecuados para formularios simples, mientras que los formularios basados en plantillas son mejores para formularios complejos.  

==C) Los formularios reactivos proporcionan una manera más programática y escalable de manejar formularios, mientras que los formularios basados en plantillas dependen más de la estructura del DOM y la lógica en el archivo HTML.  

D) Los formularios reactivos no soportan validación, mientras que los formularios basados en plantillas sí lo hacen.

~~~
**Respuesta correcta:** C  
**Explicación:** Los formularios reactivos proporcionan una manera más programática y escalable de manejar formularios en Angular, lo que permite una mejor separación de la lógica de la vista y un manejo más robusto de los datos. Los formularios basados en plantillas dependen más de la estructura del DOM y la lógica en el archivo HTML, lo que puede ser adecuado para formularios simples pero menos escalable para aplicaciones más complejas.
~~~


# ¿Cómo se puede definir una validación personalizada en un formulario reactivo en Angular?**

A) Usando la directiva `ngModel` en el archivo HTML.  

==B) Implementando una función de validación personalizada y añadiéndola al control de formulario.

C) Agregando la lógica de validación directamente en el componente HTML.

D) Usando el atributo `required` en los campos del formulario.

~~~
**Respuesta correcta:** B  
**Explicación:** En un formulario reactivo, se pueden definir validaciones personalizadas implementando una función de validación personalizada y añadiéndola al control de formulario correspondiente. Esto permite tener validaciones más complejas y específicas que las predeterminadas, asegurando que los datos del formulario cumplan con los requisitos específicos de la aplicación.
~~~

# ¿Cuál de las siguientes afirmaciones es verdadera sobre el uso de validaciones en formularios basados en plantillas en Angular?**

A) Las validaciones personalizadas no son posibles en formularios basados en plantillas.  

B) Las validaciones en formularios basados en plantillas se definen exclusivamente en el archivo TypeScript.  

==C) Las directivas `required`, `minlength` y `maxlength` se utilizan comúnmente para validar campos directamente en el archivo HTML.  

D) Los formularios basados en plantillas no permiten el uso de validadores asincrónicos.

~~~
**Respuesta correcta:** C  
**Explicación:** En los formularios basados en plantillas en Angular, es común utilizar directivas como `required`, `minlength` y `maxlength` directamente en el archivo HTML para definir las reglas de validación. Esto permite una manera declarativa y sencilla de aplicar validaciones a los campos del formulario. Las opciones A y D son incorrectas porque sí es posible definir validaciones personalizadas y asincrónicas en formularios basados en plantillas. La opción B es incorrecta porque las validaciones en formularios basados en plantillas se definen principalmente en el HTML, no en el archivo TypeScript.
~~~