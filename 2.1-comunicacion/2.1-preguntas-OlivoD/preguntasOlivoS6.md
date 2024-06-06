Video de Youtube: https://www.youtube.com/watch?v=wz0U-akBb7I 

### Pregunta 1:
¿Cuál es el propósito del decorador `@Input` en Angular?

a) Permitir que un componente hijo envíe datos a un componente padre.  
b) Permitir que un componente padre envíe datos a un componente hijo.  
c) Permitir que un componente acceda a un servicio compartido.

**Respuesta correcta:** b) Permitir que un componente padre envíe datos a un componente hijo.

**Explicación:** `@Input` se utiliza para recibir datos de un componente padre en un componente hijo.

---

### Pregunta 2:
¿Cuál de los siguientes métodos se utiliza para comunicar componentes hermanos en Angular?

a) Utilizar `@ContentChild`.  
b) Utilizar un servicio de intercambio de datos.  
c) Utilizar el decorador `@ViewChild`.

**Respuesta correcta:** b) Utilizar un servicio de intercambio de datos.

**Explicación:** Los componentes hermanos se comunican mejor mediante un servicio compartido que actúa como intermediario.

---

### Pregunta 3:
¿Qué decorador se usa en Angular para acceder a un componente hijo desde el componente padre después de que se haya inicializado la vista?

a) `@Input`  
b) `@Output`  
c) `@ViewChild`

**Respuesta correcta:** c) `@ViewChild`

**Explicación:** `@ViewChild` se usa para acceder a un componente hijo desde el componente padre una vez que la vista está inicializada.