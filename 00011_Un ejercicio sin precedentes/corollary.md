¿Y si delegamos? Podríamos separar la lógica de la siguiente manera:
 
```javascript
function puedeJubilarse(edad, sexo, aniosAportes) {
  return cumpleEdadMinima(edad, sexo) && tieneSuficientesAportes(aniosAportes);
}
```

**Al delegar correctamente**, hay veces en las que no es necesario alterar el orden de precedencia, ¡otro punto a favor de la delegación! :muscle: