# anova_two_way

Web app (HTML + JS) para:
- Subir Excel/CSV
- Mapear columnas (Tratamiento, Tipo)
- Pivotear datos wide → long
- Graficar boxplot Tratamiento × Tipo con estadísticas descriptivas anotadas (mean, median, n, sd, cv)

## Cómo usar
1. Abre `index.html` (doble click) o usa GitHub Pages.
2. Sube un Excel/CSV.
3. Elige columnas: Tratamiento, Tipo.
4. (Wide) Elige el atributo a graficar.
5. Genera el gráfico.

## Tech
- Plotly.js (gráficos)
- SheetJS (lectura Excel)
- HTML/JavaScript puro (sin backend)

## GitHub Pages (opcional)
Settings → Pages → Deploy from branch → `main` / `/root`
