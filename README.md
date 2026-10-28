# Babel

La Biblioteca de Babel, navegable en 3D con Three.js. Hexágonos infinitos y deterministas: cada sala y cada libro tienen su propia URL, y las páginas se generan por semilla a partir de las coordenadas. Entre el ruido aparecen, muy de vez en cuando, frases legibles.

**Verla online:** https://kvothesson.com/babel/

## Correrla local

Es un sitio estático, sin build:

```
python -m http.server 8000
```

y abrir http://localhost:8000/ en el navegador.

## Archivos

- `index.html`: página y mapa de imports (Three.js desde CDN)
- `babel.js`: escena, generación de salas y de páginas
- `style.css`: estilos
