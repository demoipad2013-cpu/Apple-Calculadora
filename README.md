# Financiamiento Falabella

Calculadora para vendedores de Falabella Costanera: cuotas con garantía extendida y Seguro Connect, accesorios por categoría, Exchange Planes y Seguro Compra Protegida.

## Contenido
- `index.html` — la calculadora completa (un solo archivo; logo, íconos y datos ya van incluidos).
- `datos/` — copia de las bases usadas al 11/11/2026, para consulta:
  - `exchange.json` — montos de gift card Exchange por modelo y capacidad.
  - `iphone_liberados.json` — precios de iPhone liberados (oferta y CMR).
  - `planes_apple.json` — cuotas iniciales por operador (Entel, Claro, WOM).
  - `accesorios.json` — precios normal, oferta y CMR de accesorios.
  - `garantia_watch_airpods.json` — garantía extendida 1 y 2 años.
  - `planes_iphone.json` — planes por modelo, capacidad y compañía (cuota inicial y cargo fijo).
  - `precios_apple.json` — precio automático (oferta, CMR y normal) por modelo y capacidad.
- `imagenes/` — logo de Falabella e íconos de Exchange y Compra Protegida.

## Publicar en GitHub Pages
1. Sube el contenido de esta carpeta al repositorio (por ejemplo, a la carpeta `apple/` de `costaneraelectro/garantia`).
2. Quedará en `https://costaneraelectro.github.io/garantia/apple/`.

La versión de GitHub usa los datos incluidos en `index.html`. La versión publicada en Claude se actualiza sola cada mañana a las 9:00.

## Panel de impacto y cotizador
El panel de impacto (uso por tienda, día, semana, mes y 13 semanas) y el registro de cotizaciones funcionan solo en la versión publicada en Claude, porque guardan los datos en su base compartida. En GitHub la calculadora y el cotizador por mail funcionan, pero no se registra el uso.

## Novedades (12/11/2026)
- Planes: "Así recupera el 70 %" en 3 pasos (precio oferta, cuota inicial, 70 % del precio oferta con Seguro Connect), también en la cotización. No se suma el total de los 18 meses.
- Exchange + plan: botón "¿Entrega un iPhone usado?" en Cotizar con plan; el resumen Exchange muestra el cargo fijo y el 70 % que recupera con Seguro Connect.
- Aviso naranjo cuando precios, planes o Exchange no se actualizaron.
- Modo Capacitación (botón en la barra superior): recorrido guiado; no suma al Panel de impacto.
- Celular: accesorios, beneficios Connect y argumentos Exchange plegables; Partes y piezas oculto por defecto.
- Esta versión (GitHub) no registra uso en el Panel de impacto: se muestra un aviso.
- Con plan solo se ofrece Seguro Connect Daño y Robo y Seguro Connect Daño: se ocultan la garantía extendida, el evento de garantía y la pestaña "Qué cubre la garantía".
- Cotización por correo: mensaje cordial solo en texto (sin PDF adjunto), con saludo, equipo, plan, opciones de protección, recomendación y firma del asesor.
- Exchange (antes "Exchange Planes"): financiamiento del saldo: liberado con garantía extendida 1 o 2 años (recomendada) y garantía fabricante; con plan con Seguro Connect Daño y Robo (recomendado), Seguro Connect Daño y garantía fabricante (folleto CONNECT sobre el 70 % del precio oferta); la garantía extendida se calcula sobre el precio completo del iPhone nuevo (tramo prepago), no sobre el saldo. Íconos de Exchange y Compra Protegida del mismo tamaño que el resto.
- Se eliminó el cotizador por correo (botón "Cotizar por mail").
- Seguro Connect: valores en $ del folleto CONNECT por tramo (Daño + Robo Celulares y Daño Accidental), iguales a los de tienda; la opción UF del día queda en Ajustes.
- Sin pestaña "Qué cubre la garantía" (quedan Comparar cuotas y Beneficios para ti); Partes y piezas y Accesorios ocultos por defecto con interruptor "Mostrar"; sin aviso de datos sin actualizar.
- Comparación de modelos de iPhone en Exchange: el detalle termina en Capacidad.

## Actualización 24/11/2026
- Precios de iPhone, Mac, iPad, Apple Watch y AirPods, planes Connect (Claro, Entel, WOM) y montos Exchange desde falabella.com.
- Nuevos: iPhone 17e (precio y planes), MacBook Pro 14" M6 16 GB, iMac 24" M4, iPad Air 13" M3, Apple Watch SE 3 GPS + Cellular, SE 2.ª gen, Series 9, Series 10 y Ultra 2, AirPods Max 2.
- Exchange: la comparación de modelos de iPhone queda oculta, con un botón para mostrarla.

## Actualización 26/11/2026
- Precios de iPhone (liberados y planes), Mac, iPad, Apple Watch y AirPods desde falabella.com.
- iPhone: garantía extendida de 2 años con 20 % de descuento (interruptor "Garantía 2 años −20 %", encendido por defecto).
- Campo "Gift card o pie" bajo las cuotas: se descuenta del precio elegido antes de calcular las cuotas.
