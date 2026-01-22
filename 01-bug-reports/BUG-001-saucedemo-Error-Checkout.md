Credenciales de prueba:
Username: standard_user
Password: secret_sauce

BUG REPORT 001

### TÍTULO: Codigo postal invalido en el checkout
En los campos de información de usuario  del checkout no existe un formato definido para ningún campo

### SEVERIDAD:
- [ ] ALTA (afecta funcionalidad importante)
Los campos carecen de formato, se pueden ingresar todo tipo de caracteres sin limite alguno

### PRIORIDAD:
- [ ] URGENTE (arreglar hoy)
Es pertinente solcuinarlo dado que estoy puede afectar a los registros en la base de datos

### AMBIENTE:
- **URL:https://www.saucedemo.com/checkout-step-one.html
- **Browser:** LibreWolf
- **OS:**: Linux DAT
- **Resolución:** (1920x1080)

### PRECONDICIONES:
El usuario debe estar logueado, el carrito debe tener productos en el carrito y se debe proceder con la compra

### PASOS PARA REPRODUCIR:
1. Ir a https://www.saucedemo.com/checkout-step-one.html
2. Click en campo de nombre
3. Ingresa: thiago 
4. Click en el campo de Last name: boveri
5. Postal code/Zip: 341235451245349541465536
4. Click en continue
6. Observar resultado

### RESULTADO ACTUAL:
Luego de presionar el botón “continue” se accede a la seccion de “desciption”

### RESULTADO ESPERADO:
Al presionar el boton “continue” se deberia de indicar que el formato de el codigo postal es invalido 

### EVIDENCIA: no la puedo adjuntar ya que te voy a mandar solo texto pero lo tendre en cuenta para un caso real
- Screenshot: [adjuntar]
- Video: [adjuntar si es necesario]
- Logs de consola: [si aplica]

### NOTAS ADICIONALES:
Ocurre siempre
No hay patron especifico es un error de un solo campo
No

---
**Reportado por:** Thiago Boveri
**Fecha:** 2026-01-19
