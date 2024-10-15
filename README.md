# **Ejercicio Físicas 3D**:

### **Situación 1**:
**Descripción**: El plano no es un objeto físico. El cubo es un objeto físico y la esfera no. En este caso, el plano y la esfera sólo tendrán collider, mientras que el cubo debe tener Rigidbody. 

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion1.gif)

**Resultado**:
- El plano actúa como una superficie fija e inmóvil, pero no afectará a la física.
- El cubo, con Rigidbody, será afectado por la gravedad y caerá sobre el plano, quedándose inmóvil sobre él.
- La esfera, sin Rigidbody, no será afectada por la gravedad, se mantendrá en su posición flotante.

---

### **Situación 2**:
**Descripción**: El plano no es un objeto físico. El cubo es un objeto físico y la esfera también. En este caso, el plano sólo tendrán collider, mientras que el cubo y la esfera deben tener Rigidbody. 

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion2.gif)

**Resultado**:
- El plano actúa como una superficie que evita que los objetos atraviesen el suelo.
- El cubo caerá debido a la gravedad y se quedará sobre el plano.
- La esfera, con Rigidbody caerá y colisionará con el cubo.

---

### **Situación 3**:
**Descripción**: El plano no es un objeto físico. El cubo es un objeto físico y la esfera es cinemática. En este caso, el plano sólo tendrán collider, mientras que el cubo y la esfera deben tener Rigidbody esta última cinemático. 

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion3.gif)

**Resultado**:
- El plano sigue siendo solo una superficie de colisión.
- El cubo caerá al plano y permanecerá inmóvil sobre él.
- La esfera, al ser cinemática, no será afectada por la gravedad, pero puede moverse si es controlada por un script.

---

### **Situación 4**:
**Descripción**: El plano es un objeto físico. El cubo es un objeto físico y la esfera es física. En este caso, todos los objetos deben tener Rigidbody.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion4.gif)

**Resultado**:
- El plano ahora es un objeto físico, lo que significa que se comportará como una plataforma sólida.
- El cubo y la esfera caerán debido a la gravedad.

---

### **Situación 5**:
**Descripción**: El plano es un objeto físico. El cubo es un objeto físico y la esfera es física con 10 veces más masa que el cubo. En este caso, todos los objetos deben tener Rigidbody.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion5.gif)

**Resultado**:
- Todos los elementos caen, y la diferencia de masa de la esfera no se vuelve apreciable debido al efecto también visto en el experimento de Galileo.

---

### **Situación 6**:
**Descripción**: El plano es un objeto físico. El cubo es un objeto físico y la esfera es física con 100 veces más masa que el cubo. En este caso, todos los objetos deben tener Rigidbody.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion6.gif)

**Resultado**:
- Igual que antes todos los objetos se comportan igual y la diferencia de masa de la esfera no se aprecia.

---

### **Situación 7**:
**Descripción**: El plano es un objeto físico. El cubo es un objeto físico y la esfera es física con fricción. En este caso, todos los objetos deben tener Rigidbody.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion7.gif)

**Resultado**:
- Si la esfera tiene fricción, cuando caiga sobre el cubo o el plano, su movimiento será frenado por la fricción, lo que reducirá su deslizamiento en las superficies.
- Pero aún así todos caerán de la misma manera que antes.

---

### **Situación 8**:
**Descripción**: El plano es un objeto físico. El cubo es un objeto físico y la esfera no es física y es Trigger. En este caso, todos los objetos deben tener Rigidbody.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion8.gif)

**Resultado**:
- El cubo y el plano caerán normalmente.
- La esfera al ser un trigger no caerá. Podría activar eventos como detección de entrada/salida de un área si otros objetos entran en su volumen.

---

### **Situación 9**:
**Descripción**: El plano es un objeto físico. El cubo es un objeto físico y la esfera es física y es Trigger. En este caso, todos los objetos deben tener Rigidbody.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Situacion9.gif)

**Resultado**:
- El cubo y el plano caerán normalmente.
- La esfera caerá debido a la gravedad, pero no colisionará con el cubo ni con el plano al ser un trigger.

---
# **Ejercicios Práctica 3**

### **Ejercicio 1**:
**Descripción**: Agrega un campo velocidad a un cubo y asígnale un valor que se pueda cambiar en el inspector de objetos. Muestra la consola el resultado de multiplicar la velocidad por el valor del eje vertical y por el valor del eje horizontal cada vez que se pulsan las teclas flecha arriba-abajo ó flecha izquierda-derecha. El mensaje debe comenzar por el nombre de la flecha pulsada.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Ejercicio1.gif)

---

### **Ejercicio 2**:
**Descripción**: Mapea la tecla H a la función disparo. 

**FOTO:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Ejercicio2.png)

---

### **Ejercicio 3**:
**Descripción**: Crea un script asociado al cubo que en cada iteración traslade al cubo una cantidad proporcional un vector que indica la dirección del movimiento: moveDirection que debe poder modificarse en el inspector.  La velocidad a la que se produce el movimiento también se especifica en el inspector, con la propiedad speed. Inicialmente la velocidad debe ser mayor que 1 y el cubo estar en una posición y=0. En el informe de la práctica comenta los resultados que obtienes en cada una de las siguientes situaciones:

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Ejercicio3.gif)

---

### **Ejercicio 4**:
**Descripción**: Mueve el cubo con las teclas de flecha arriba-abajo, izquierda-derecha a la velocidad speed. Cada uno de estos ejes implican desplazamientos en el eje vertical y horizontal respectivamente. Mueve la esfera con las teclas w-s (movimiento vertical) a-d (movimiento horizontal).

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Ejercicio4.gif)

---

### **Ejercicio 5**:
**Descripción**: Adapta el movimiento en el ejercicio 4 para que sea proporcional al tiempo transcurrido durante la generación del frame.

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Ejercicio5.gif)

---

### **Ejercicio 6**:
**Descripción**: Adapta el movimiento en el ejercicio 5 para que el cubo se mueva hacia la posición de la esfera. Debes considerar, que el avance no debe estar influenciado por cuánto de lejos o cerca estén los dos objetos. 

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Ejercicio6.gif)

---

### **Ejercicio 7**:
**Descripción**: Adapta el movimiento en el ejercicio 6 de forma que el cubo gire hacia la esfera. Realiza pruebas cambiando la posición de la esfera mediante las teclas awsd. 

**GIF:**
![](https://github.com/alu0101493084/II-Pract3/blob/main/II-Pract3%20-%20Ejercicio7.gif)

---

### **Ejercicio 8**:
**Descripción**: Utilizar el eje “Horizontal” para girar el objetivo y que avance siempre en la dirección hacia adelante.

**GIF:**
![]()

---

### **Ejercicio 9**:
**Descripción**: Configura el cilindro como un objeto físico, cuando el cubo o la esfera colisionen con él se debe mostrar un mensaje en consola con la etiqueta del objeto que haya colisionado. 

**GIF:**
![]()

---

### **Ejercicio 10**:
**Descripción**: Configura el cubo como un objeto cinemático y la esfera como un objeto físico. Adapta los scripts del ejercicio 9 para obtener el mismo comportamiento. 

**GIF:**
![]()

---

### **Ejercicio 11**:
**Descripción**: Configura el cilindro como un objeto de tipo Trigger. Adapta los scripts de los ejercicios anteriores para obtener el mismo comportamiento.

**GIF:**
![]()

---

### **Ejercicio 12**:
**Descripción**: Agrega un cilindro de un color diferente al que ya hay en la escena y configúralo como un objeto físico. Selecciona un conjunto de teclas que te permitan controlar su movimiento por la escena y prográmale un movimiento que permita dirigirlo hacia la esfera. Prueba diferentes configuraciones de la esfera física con masa 10 veces mayor que el cilindro, física con masa 10 veces menor que el cilindro, cinemática y trigger. También prueba la configuración del cilindro de forma que su fricción se duplique o no. Explica en el informe todos los resultados posibles.

**GIF:**
![]()

---
