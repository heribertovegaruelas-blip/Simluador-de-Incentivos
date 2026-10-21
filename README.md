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
Las tablas de bloques, cobranza y tramos de afiliación están al inicio del `<script>` de `index.html` (constantes `EJ`, `GE`, `RE`, `EFF`, `AF_EJ`, `AF_GE` y `AF_RE`). La fórmula que se muestra en el encabezado está en `FORMULA`. Los umbrales de la campaña están en `campana.html` (`TIERS`, `DIA` y `TOP`).

## Versión actual
Presentación ejecutiva de octubre 2026 (actualización del 21/10/2026):
- Bloques C1–C16 (ejecutivo), G1–G16 (gerente de sucursal) y B1–B21 (regional, trimestral; el salto de $500 a $10,000 ya está incluido en la base de cada bloque).
- Cobranza multiplica la colocación en los tres niveles (0 a 1.30x).
- Afiliación se paga por tramos en los tres niveles, con bono de entrada la primera vez:
  - Ejecutivo: de $200 (1 afiliación) a $40,000 (31 o más).
  - Gerente: afiliaciones de la sucursal en el mes, de $200 (5–10) a $35,000 (101 o más).
  - Regional: afiliaciones de la región en el trimestre, de $1,000 (101–200) a $50,000 (701 o más).
- Gerente y regional: candados de rentabilidad (15%) y auditoría (95%). Regional: bono anual de 3 meses con rentabilidad arriba de 20% y EBITDA Capta al 85%.
- Ya no aplican el multiplicador de afiliación por % de meta ni el × 1.10 del ejecutivo por meta de sucursal.
- Campaña "Suma aliadas a tu red" (hoja aparte): día de descanso con 6+ afiliaciones válidas al mes (máximo 3), condición de 2+ válidas cada mes y paquetes Plata (20–25), Oro (26–35) y Platino (36+); Top 3 nacional con mínimo 45.

El logo está en `assets/logo.png`.
