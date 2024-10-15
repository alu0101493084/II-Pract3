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

