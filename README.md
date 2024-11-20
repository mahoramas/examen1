# Examen teórico
## Ejercicio 1 Tienda de Comercio Electrónico
<img src="Diagrama/Tienda de Comercio Electrónico.drawio.png">

---
## Ejercicio 2 Realiza la especificación de Casos de Uso
|  Actor | Cliente |
|---|---|
| Descripción  | _Cliente que puede realizar algunas acciones_  |
| Características  | __ |
| Relaciones | __  |
| Referencias | _Proporcionar datos personales, Alquilar Película, Reservar Película, Devolver Película, Seleccionar Película_ |
|  Notas |  __ |
| Autor  | _Marcos Hernández Oramas_ |
|Fecha | _20/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

---

|  Actor | Proveedor |
|---|---|
| Descripción  | _Proveedor que puede realizar algunas acciones_  |
| Características  | __ |
| Relaciones | _Abastecer película_  |
| Referencias | _Abastecer Película segun existencia_ |
|  Notas |  __ |
| Autor  | _Marcos Hernández Oramas_ |
|Fecha | _20/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

---

|  Actor | Administrador |
|---|---|
| Descripción  | _Administrador que puede realizar algunas acciones_  |
| Características  | __ |
| Relaciones | _Abastecer película_  |
| Referencias | _Registrar cliente, Registrar alquilar, Registrar reserva, Registrar película, Actualizar proveedor_ |
|  Notas |  __ |
| Autor  | _Marcos Hernández Oramas_ |
|Fecha | _20/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

---

 |  Caso de Uso	CU | Proporcionar Datos Personales |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Cliente_ |
  | Descripción | _El actor da sus datos_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

   |  Caso de Uso	CU | Alquilar Película |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Cliente_ |
  | Descripción | _El actor alquila una pelicula_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Seleccionar película_  |
  | Post-condiciones  | _Devolver película_  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

   |  Caso de Uso	CU | Reserva Película |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Cliente_ |
  | Descripción | _El actor reserva una película_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Seleccionar película_  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

   |  Caso de Uso	CU | Seleccionar Película |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Cliente_ |
  | Descripción | _El actor selecciona una película_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

|  Caso de Uso	CU | Devolver Película |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Cliente_ |
  | Descripción | _El actor devuelve una película_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Alquilar película_  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

|  Caso de Uso	CU | Abastecer Película segun existencias |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Proveedor_ |
  | Descripción | _El actor abastece películas segun existencias_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |
  | Post-condiciones  | _Abastecer película_  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

|  Caso de Uso	CU | Abastecer Película |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Proveedor, Administrador_ |
  | Descripción | _El actor seleccionar película_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

|  Caso de Uso	CU | Registrar a los clientes |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Administrador_ |
  | Descripción | _El actor registra a los clientes_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Cliente proporciona datos personales_  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

|  Caso de Uso	CU | Registrar Alquiler |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Administrador_ |
  | Descripción | _El actor registra el alquiler_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Cliente alquile una película_  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

  |  Caso de Uso	CU | Registrar Reserva |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Administrador_ |
  | Descripción | _El actor registra la reserva_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Cliente reserve una película_  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

  |  Caso de Uso	CU | Registrar Película |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Administrador_ |
  | Descripción | _El actor registra una película_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Proveedor abastece una película_  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---

  |  Caso de Uso	CU | Actualiza Proveedor |
  |---|---|
  | Fuentes  | __  |
  | Actor  |  _Administrador_ |
  | Descripción | _El actor actualiza al proveedor_  |
  | Flujo básico | __ |
  | Pre-condiciones | __  |
  | Post-condiciones  | __  |
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Marcos Hernández Oramas_ |
  |Fecha | _20/11/2024_ |

  ---
