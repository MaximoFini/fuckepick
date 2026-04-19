# Modelo de Pricing por Tamaño — Resumen Ejecutivo

## Modelo Actual
La empresa aplica un **precio fijo** para todos los paquetes de hasta **15.552 cm³**, sin distinción de peso ni densidad. Por encima de ese umbral, el precio sube $0,50 por cm³ adicional.

---

## El Problema
Dentro del umbral, **un libro y dos cajas de zapatos apiladas pagan exactamente lo mismo**. Esto genera un subsidio encubierto: los paquetes voluminosos y livianos ocupan hasta 28x más espacio en el vehículo que los paquetes densos, reduciendo la capacidad operativa disponible sin que eso tenga ningún reflejo en el precio.

> El modelo actual **premia al cliente ineficiente** y castiga la densidad de la flota.

---

## La Solución Propuesta: Densidad Mínima

Incorporar un **factor de peso volumétrico** como variable de control:

```
Si (peso real / volumen) < umbral mínimo de densidad
→ cobrar usando el peso volumétrico en lugar del peso real
```

En simple: *si tu paquete es muy grande para lo poco que pesa, se cobra como si pesara más.*

Este mecanismo **no modifica el modelo para la mayoría de los clientes**, solo corrige los casos donde el volumen está siendo subsidiado por el precio plano.

> ✅ Este es exactamente el modelo que aplican **FedEx, UPS y DHL** a nivel global bajo el nombre de *dimensional weight pricing* — una práctica estándar en la industria logística internacional.