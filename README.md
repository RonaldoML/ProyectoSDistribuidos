## Para correr el proyecto
1) npm install
2) npm run build
3) npm start

## Links importantes

### Explicacion breve de la infraestructura del proyecto

https://groundberry.github.io/development/2016/11/04/build-your-node-app-with-express-and-sequelize.html 

### Joins como hacerlos en sequelize

http://lorenstewart.me/2016/09/12/sequelize-table-associations-joins/ 

### Uso de mocha

http://mherman.org/blog/2015/09/10/testing-node-js-with-mocha-and-chai/#.WS9s9mg19Eb 

## Version

Estado Actual es : 0.0.1

## Documentacion

Cada clase y archivo del proyecto debe tener cuatro cosas:

* Una descripcion de lo que la clase o archivo hace
* Autor
* La fecha de creacion del documento
* La ultima modificacion del documento y quien lo hizo

EJ 

```

/*
@Descripcion: esta es una clase poligono
@Autor: jose viteri
@FechaCreacion: 19/05/2017
@UltimaFechaModificacion: 25/05/2017 @EdisonMora

*/
class Poligono {
  constructor(alto, ancho) {
    this.alto = alto;
    this.ancho = ancho;
  }
}
```

Esto tambien debe aplicarse a las funciones cuya funcionalidad no queda clara con su nombre
