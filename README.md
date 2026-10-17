# Simulador de incentivos Captavale

Dos hojas con el mismo diseño:
- `index.html` · **Esquema de incentivos**: ejecutivo de cuenta, gerente de sucursal y gerente regional.
- `campana.html` · **Campaña Suma aliadas a tu red**: días de descanso y paquetes de premios del trimestre para ejecutivas.

Los estilos compartidos están en `assets/estilo.css`.

Página para que cada ejecutivo de cuenta, gerente de sucursal y gerente regional estime su incentivo con el nuevo esquema por bloques y reciba tips cuando su cobranza, afiliación o candados están bajos.

## Publicar en GitHub Pages
1. Sube `index.html`, `campana.html` y la carpeta `assets` a la raíz del repositorio.
2. En el repositorio ve a **Settings › Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
3. En un par de minutos la página queda en `https://<tu-usuario>.github.io/simulador-incentivos/`.

## Actualizar tablas
Las tablas de bloques, multiplicadores y tramos de afiliación están al inicio del `<script>` de `index.html` (constantes `EJ`, `GE`, `RE`, `EFF` y `AF`). La fórmula que se muestra en el encabezado está en `FORMULA`.

## Versión actual
Esquema de la presentación ejecutiva del 16/10/2026:
- Bloques E1–E16 (ejecutivo), G1–G16 (gerente de sucursal) y R1–R21 (regional).
- Afiliación de gerente y regional por debajo de 90%: × 0.50.
- Ejecutivo: × 1.10 a la colocación si su sucursal cumple el 100% de su meta de afiliación.
- Campaña "Suma aliadas a tu red" (hoja aparte): día de descanso con 4+ afiliaciones válidas al mes (máximo 3), condición de 2+ válidas cada mes y paquetes Plata (15–20), Oro (21–29) y Platino (30+); Top 3 nacional con mínimo 35.

El logo está en `assets/logo.png`.
