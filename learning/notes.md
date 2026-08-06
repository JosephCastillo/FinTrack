# Notas

## US-001 - Registrar ingresos (Plantilla)

### Historia

**Como** usuario

**Quiero** registrar mis ingresos

**Para** llevar un control de mi dinero y conocer cuánto ingreso durante cada período.

### Prioridad

Alta

### Criterios de aceptación

- ...
- ...
- ...

---

# Cada historia debe responder estas preguntas

| Pregunta                          | Ejemplo                        |
| --------------------------------- | ------------------------------ |
| ¿Quién obtiene valor?             | Usuario                        |
| ¿Qué quiere hacer?                | Registrar ingresos             |
| ¿Por qué lo necesita?             | Llevar el control de su dinero |
| ¿Cómo sabemos que está terminada? | Criterios de aceptación        |

# Refinamiento para historias de usuario

| **Campo**                     | **¿Por qué es útil?**                                    |
| ----------------------------- | -------------------------------------------------------- |
| Monto                         | Permite calcular el saldo y los totales.                 |
| Categoría                     | Permite analizar en qué se gasta el dinero.              |
| Tipo (necesario/no necesario) | Permite identificar gastos prescindibles.                |
| Fecha                         | Permite generar reportes diarios, semanales y mensuales. |
| Descripción                   | Aporta contexto cuando el usuario revisa un movimiento.  |


# Diseño de productos

| Pregunta del usuario             | Indicador                 |
| -------------------------------- | ------------------------- |
| ¿Cuánto dinero tengo?            | Saldo disponible          |
| ¿Cuánto he recibido este mes?    | Ingresos del mes          |
| ¿Cuánto he gastado?              | Gastos del mes            |
| ¿Qué fue lo último que registré? | Últimos movimientos       |
| ¿En qué gasto más?               | Categoría con mayor gasto |
