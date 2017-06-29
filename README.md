#Platzom

Platzom es un idioma inventado para el Curso de Fundamentos de JavaScript.

## Descripción del idioma
-si la palabra termina en "ar" se le quita esos dos cararcteres
-si la palabra inicia comn Z, se le añade "pe" al final
-si la plabra traducida tiene 10 o mas letras
-se le parte a la mitad y unir con un guion del medio.
-si la palabra original es un palindromo 
-ninguna regla anterior cuenta y se devuelve las misma palabra intercalando mayusculas y minusculas.

## Instalación
```
npm install platzom
```

## Uso
```
import platzom from 'platzom'
``

console.log(platzom("Programar")) //Program
console.log(platzom("Zorro")) //Zorrope
console.log(platzom("Zarpar")) // Zarppe
console.log(platzom("abecedario"))//abece-dario
console.log(platzom("sometemos"))//SoMeTeMoS

## Créditos
- [Jaime Repizo](http://www.jaimerepizo.com)

## Licencia
[MIT](https://opensource.org/licenses/MIT)
