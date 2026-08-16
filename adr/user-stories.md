# Historias de usuario

## Información del documento

| Campo | Valor |
|-------|-------|
| Estado | 🟡 En elaboración |
| Versión | 0.1 |
| Autor | Joseph Castillo |
| Última actualización | 4 agosto 2026 |

---

# Introducción

Este documento contiene las historias de usuario del proyecto FinTrack. Las historias describen las funcionalidades desde la perspectiva del usuario y sirven como base para la  contrucción del ***Product Backlog***, la definición de requisitos funcionales y la planificación del desarrollo.

---

# Épicas

## EP-001 - Gestión de usuarios

Permite al usuario crear una cuenta, autenticarse y gestionar su acceso a FinTrack.

### Historias relacionadas

- US-001 - Registrar usuario
- US-002 - Iniciar sesión


## EP-002 - Gestión financiera

Permite al usuario registrar sus ingresos y gastos en FinTrack.

### Historias relacionadas

- US-003 - Registrar ingresos
- US-004 - Registrar gastos


## EP-003 - Consulta financiera

Permite al usuario consultar su estado financiero y obtener información para tomar mejores decisiones sobre su dinero.

### Historias relacionadas

- US-005 - Consultar Dashboard

---

## US-001 - Registrar usuario

### Historia

**Como** usuario
**Quiero** registrarme en FinTrack
**Para** almacenar mi información de forma segura y acceder a mis finanzas personales

### Prioridad

> Alta

### Estado

> Pendiente

### MVP

> Si


### Criterios de aceptación

- El sistema debe permitir ingresar el nombre completo.
- El sistema debe permitir ingregar un correo electrónico válido.
- El sistema debe permitir crear una constraseña.
- El sistema debe validar que el correo no esté registrado previamente.
- El sistema debe validar que todos los campos obligatorios estén completos.
- Al finalizar el registro, debe crearse una cuenta para el usuario.




## US-002 - Iniciar sesión

### Historia

**Como** usuario
**Quiero** iniciar sesión en FinTrack
**Para** acceder de forma segura a mi información financiera y continuar administrando mis finanzas personales.

### Prioridad

>Alta

### Estado 

>Pendiente

### MVP

>Si

### Criterios de aceptación
- El sistema debe permitir ingresar correo.
- El sistema debe permitir ingresar contraseña.
- El sistema debe validar que el correo y la contraseña correspondan a un usuario registrado.
- Al iniciar sesión correctamente, el sistema debe redirigir al usuario al Dashboard.
- El sistema debe informar al usuario si los datos introducidos son incorrectos.
- El sistema debe mostrar la opción de recuperar contraseña.
- El sistema no debe permitir iniciar sesión con campos obligatorios vacíos.




## US-003 - Registrar ingresos

### Historia

**Como** usuario
**Quiero** registrar mis ingresos
**Para** llevar un control de mi dinero y conocer cuánto ingreso durate cada periodo.

### Prioridad

>Alta

### Estado 

>Pendiente

### MVP

>Si

### Criterios de aceptación

- Debe permitir registrar el monto.
- Debe permitir seleccionar el origen del ingreso.
- Debe permitir seleccionar la categoría.
- Debe permitir agregar una descripción.
- Debe registrar la fecha.
- Debe actualizar automáticamente el saldo.
- De aparecer en el hitorial.
- Debe informar al usuario el registro exitoso del ingreso.
- Debe informar si ocurrió un error al registrar el ingreso.


## US-004 - Registrar Gastos

### Historia

**Como** usuario
**Quiero** registrar mis gastos
**Para** comprender mis hábitos de consumo y controlar mejor mis finanzas personales.

### Prioridad

>Alta

### Estado

>Pendiente

### MVP

>Si

### Criterios de aceptación

- Debe permitir registar el monto.
- Debe permitir registrar la categoría.
- Debe registrar la fecha autoamticamente.
- Debe permitir registrar una descripción.
- Debe permitir registrar el tipo de gasto.
- Debe informar si el registro se realizó correctamente.
- Debe infromar si surguió un error.
- Debe actualizar automatimáticamente el saldo disponible.
- El gasto registrado debe aparecer en el historial de movimientos.

## US-005 Consultar Dashboard

### Historio

**Como** usuario
**Quiero** consultar un resumen de la información más relevante de mis finanzas
**Para** conocer mi situación financiera y tomar mejores decisiones sobre mi dinero.

### Prioridad

>Alta

### Estado

>Pendiente

### MVP
>Si

### Criterios de aceptación

- Debe mostrar saludo con el nombre de usuario.
- Debe mostrar el saldo disponible.
- Debe mostrar un botón para registrar un ingreso.
- Debe mostrar un botón para registrar un gasto.
- Debe mostrar ingresos del periodo.
- Debe mostrar gastos del periodo.
- Debe mostrar la categoria con mayor gasto.
- Debe mostrar movimientos.
- Si el usuario no tiene movimientos registrados, debe mostrar un mensaje indicándolo.
- Si el usuario aún no ha registrado ingresos, debe invitarlo a registrar el primero.
- Si no existen movimientos, los indicadores financieros deben mostrarse con valor cero.

