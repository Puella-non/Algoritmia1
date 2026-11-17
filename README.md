# Algoritmia 1 — Índice de ejercicios

Repositorio con los ejercicios de la asignatura, organizados por sesión. Los algoritmos están escritos en **PSeInt** (archivos `.psc`).

## Cómo abrir los ejercicios

1. Instala PSeInt: https://pseint.sourceforge.net
2. Abre PSeInt y ve a **Archivo > Abrir**.
3. Selecciona el archivo `.psc` que quieras.
4. Pulsa **Ejecutar** (F9).

## Estructura general

```
Algoritmia1/
├── sesion-01/
│   ├── algoritmia-s1/
│   └── rueda-libre-algoritmia/
├── sesion-02/
└── sesion-03/
```

---

## Sesión 01

### `sesion-01/algoritmia-s1/` — Ejercicios de la sesión

La carpeta incluye un `README.md` con las pruebas de cada programa y una carpeta `diagramas/` con los diagramas de flujo.

| Ejercicio | Descripción | Algoritmo | Diagrama |
|---|---|---|---|
| Saludo | Pide el nombre y da la bienvenida | [Saludo.psc](sesion-01/algoritmia-s1/Saludo.psc) | [Saludo.svg](sesion-01/algoritmia-s1/diagramas/Saludo.svg) |
| Propinas | Calcula propina, total de la cuenta y valor por persona | [Propinas.psc](sesion-01/algoritmia-s1/Propinas.psc) | [Propinas.svg](sesion-01/algoritmia-s1/diagramas/Propinas.svg) |
| Promedio de notas | Promedio de tres notas (0 a 5) | [PromedioNotas.psc](sesion-01/algoritmia-s1/PromedioNotas.psc) | [PromedioNotas.svg](sesion-01/algoritmia-s1/diagramas/PromedioNotas.svg) |
| Edad en días | Convierte la edad a meses, semanas y días | [EdadEnDias.psc](sesion-01/algoritmia-s1/EdadEnDias.psc) | [EdadEnDias.svg](sesion-01/algoritmia-s1/diagramas/EdadEnDias.svg) |
| Pasos para hacer un tinto | Algoritmo descrito en pasos (lenguaje natural) | [tinto.md](sesion-01/algoritmia-s1/tinto.md) | — |

Pruebas de todos los programas: [README de algoritmia-s1](sesion-01/algoritmia-s1/README.md)

### `sesion-01/rueda-libre-algoritmia/` — Proyecto Rueda Libre (asistente de taquilla)

Proyecto para un negocio de alquiler de bicicletas y recorridos guiados. Documentación general: [README del proyecto](sesion-01/rueda-libre-algoritmia/README.md)

| Ejercicio | Descripción | Algoritmo | Diagrama |
|---|---|---|---|
| Cotización básica | Cotiza el alquiler de una bicicleta urbana por horas | [cotizacion_basica.psc](sesion-01/rueda-libre-algoritmia/algoritmos/cotizacion_basica.psc) | — |
| Cotización de recorrido | Cotiza un recorrido guiado con anticipo del 30 % | [cotizacion_recorrido.psc](sesion-01/rueda-libre-algoritmia/algoritmos/cotizacion_recorrido.psc) | [cotizacion_recorrido.svg](sesion-01/rueda-libre-algoritmia/diagramas/cotizacion_recorrido.svg) |
| Cuenta del grupo | Alquiler + recorrido + aporte voluntario del 10 %, y valor por persona | [cuenta_grupo.psc](sesion-01/rueda-libre-algoritmia/algoritmos/cuenta_grupo.psc) | [cuenta_grupo.svg](sesion-01/rueda-libre-algoritmia/diagramas/cuenta_grupo.svg) |
| Bitácora | Pasos para alquilar una bicicleta, con criterios de algoritmo y pilares del pensamiento computacional | [bitacora.md](sesion-01/rueda-libre-algoritmia/bitacora.md) | — |

---

## Sesión 02 — Condicionales

Las pruebas y la tabla de verdad de cada ejercicio están en el [README de la sesión 02](sesion-02/README.md).

| Ejercicio | Descripción | Algoritmo |
|---|---|---|
| Validar registro | Registro si edad ≥ 14 y acepta los términos (incluye tabla de verdad) | [ValidarRegistro.psc](sesion-02/ValidarRegistro.psc) |
| Validar edad | Verifica que la edad esté entre 0 y 120 | [ValidarEdad.psc](sesion-02/ValidarEdad.psc) |
| Parqueadero | Valor a pagar según tipo de vehículo, tiempo y factura de compra | [Parqueadero.psc](sesion-02/Parqueadero.psc) |
| Semáforo | Estado del inventario (rojo, amarillo, verde) según unidades | [Semaforo.psc](sesion-02/Semaforo.psc) |
| Año bisiesto | Indica si un año es bisiesto | [Bisiesto.psc](sesion-02/Bisiesto.psc) |

---

## Sesión 03 — Ciclos y subprocesos

Las pruebas y las tablas de traza están en el [README de la sesión 03](sesion-03/README.md).

| Ejercicio | Descripción | Algoritmo |
|---|---|---|
| Validar PIN | Máximo 3 intentos para ingresar el PIN; bloquea la tarjeta | [ValidarPin.psc](sesion-03/ValidarPin.psc) |
| Cajero parqueadero | Suma los valores cobrados y cuenta los carros hasta cerrar caja (0) | [CajeroParqueadero.psc](sesion-03/CajeroParqueadero.psc) |
| Calificaciones | Promedio, aprobados, nota más alta y más baja de 5 estudiantes | [Calificaciones.psc](sesion-03/Calificaciones.psc) |
| Pirámide | Dibuja una pirámide de asteriscos con la altura indicada | [Piramide.psc](sesion-03/Piramide.psc) |
| Factura restaurante | Factura con impuesto (8 %) y propina (10 %) usando funciones y subproceso | [FacturaRestaurante.psc](sesion-03/FacturaRestaurante.psc) |
| Árbol de componentes (Mercado Libre) | Análisis de los componentes de la página principal | Sección al final del [README de la sesión 03](sesion-03/README.md) |
