#  CampusCar

Sistema de diseño de base de datos para un concesionario de vehículos desarrollado como proyecto académico.

El modelo permite administrar clientes, vendedores, vehículos, ventas y mantenimientos, garantizando la integridad de la información mediante restricciones y reglas de negocio implementadas directamente en la base de datos.

---

##  Estructura del proyecto

```
CampusCar
│
├── README.md
├── documentacion(1).pdf
│
├── diagramas
│   ├── diagrama_er.png
│   └── diagrama_mer.png
```

---

##  Funcionalidades

- Gestión de clientes.
- Gestión de vendedores.
- Administración del inventario de vehículos.
- Registro de ventas.
- Asociación de varios vehículos a una misma venta.
- Registro de mantenimientos.

---

##  Modelo de Base de Datos

El modelo está compuesto por seis entidades principales:

- Cliente
- Vendedor
- Vehiculo
- Venta
- Detalle_venta
- Mantenimiento

Fue normalizado hasta la **Tercera Forma Normal (3FN)** para reducir redundancias y mantener la integridad de los datos.

---

##  Diagramas

### Modelo Entidad-Relación

![Diagrama ER](diagramas/diagrama_er.png)

### Modelo MER

![Modelo MER](diagramas/diagrama_mer.png)

---

##  Reglas implementadas

- Claves primarias y foráneas.
- Restricciones `UNIQUE`.
- Integridad referencial.

---

##  Tecnologías

- Mermaid

---

##  Documentación

La explicación detallada del diseño, diccionario de datos, relaciones, cardinalidades y reglas de negocio se encuentra en el archivo **documentacion(1).pdf**.

---

##  Autor

**Frayden Stiven Garcia Urbina**

Campuslands - Julio 2026