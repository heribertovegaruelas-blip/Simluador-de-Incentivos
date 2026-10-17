# Simulador de incentivos Captavale

Página para que cada ejecutivo de cuenta, gerente de sucursal y gerente regional estime su incentivo con el nuevo esquema por bloques y reciba tips cuando su cobranza, afiliación o candados están bajos.

## Publicar en GitHub Pages
1. Crea un repositorio (por ejemplo `simulador-incentivos`) y sube `index.html` a la raíz.
2. En el repositorio ve a **Settings › Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
3. En un par de minutos la página queda en `https://<tu-usuario>.github.io/simulador-incentivos/`.

## Actualizar tablas
Las tablas de bloques, multiplicadores y tramos de afiliación están al inicio del `<script>` de `index.html` (constantes `EJ`, `GE`, `RE`, `EFF` y `AF`). La fórmula que se muestra en el encabezado está en `FORMULA`.

## Versión actual
Esquema de la presentación ejecutiva del 16/10/2026:
- Bloques E1–E16 (ejecutivo), G1–G16 (gerente de sucursal) y R1–R21 (regional).
- Afiliación de gerente y regional por debajo de 90%: × 0.50.
- Ejecutivo: × 1.10 a la colocación si su sucursal cumple el 100% de su meta de afiliación.
- Campaña "Suma aliadas a tu red" para ejecutivas: día de descanso con 4+ afiliaciones válidas al mes y paquetes Plata (15–20), Oro (21–29) y Platino (30+) al cierre del trimestre.

El logo está en `assets/logo.png`.
