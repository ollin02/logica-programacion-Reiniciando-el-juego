# 09 Desafío: hora de practicar
<p>Desafíos: Saber cómo usar funciones es uno de los conceptos fundamentales en la programación y el desarrollo de software. 
  Las funciones desempeñan un papel crucial en la organización, modularización y reutilización del código.</p>
<p>Con eso en mente, hemos creado una lista de actividades (opcionales) centradas en la práctica para mejorar aún más tu experiencia de aprendizaje.
  ¡Así que vamos a practicar!</p>

  ## Desafíos:
  1. Crea una función que calcule el índice de masa corporal (IMC) de una persona a partir de su altura en metros y peso en kilogramos, que se recibirán como parámetros.
```javascript
    function IndiceMasaCorporal(peso, altura){
        let imc = peso / Math.pow(altura,2);
        return imc
    }

    IndiceMasaCorporal(68, 1.76);
```
2. Crea una función que calcule el valor del factorial de un número pasado como parámetro.
```javascript
    function factorial(valor){
        if(valor === 0 || valor === 1){
          return 1;
        }
      return valor * factorial(valor-1);
    }
    let numero = 3
    let resultado =  factorial(numero);
    console.log(`El factorial de ${numero} es ${resultado}`);
```
3. Crea una función que convierta un valor en dólares, pasado como parámetro,
  y devuelva el valor equivalente en reales(moneda brasileña,
  si deseas puedes hacerlo con el valor del dólar en tu país). Para esto, considera la cotización de un dólar igual a R$5.84.
```javascript
    let valorDelDolarEnReales = 5.844;

    function conversor(dolares, valorDelDolarEnReales){
        return dolares * valorDelDolarEnReales;
    }

    let valor = 5
    console.log(`USD $ ${valor} corresponden a R $ ${conversor(valor, valorDelDolarEnReales)}`);
```
4. Crea una función que muestre en pantalla el área y el perímetro de una sala rectangular,
   utilizando la altura y la anchura que se proporcionarán como parámetros.
```javascript
    function areaPerimetro(base, altura){
        console.log(`Rectangulo de base : ${base} y de altura: ${altura} el perimetro es: ${2*base+2*altura} y el area es: ${base*altura}`);
    }

    let base = 5;
    let altura = 6;
    areaPerimetro(base,altura);
```
5. Crea una función que muestre en pantalla el área y el perímetro de una sala circular, utilizando su radio que se proporcionará como parámetro. Considera Pi = 3,14.
```javascript
    function circuloAreaPerimetro(radio){
        const PI = 3.141516;
        console.log(`El circulo de radio ${radio} tiene de perimetro ${2*PI*radio} y de area ${PI*radio*radio}`); 
    }

    let radio = 5
    circuloAreaPerimetro(radio);
```   
6.Crea una función que muestre en pantalla la tabla de multiplicar de un número dado como parámetro.
```javascript
    function tablaMultiplicar(numero){
         for(var i=1; i<=10; i++){
            var resultado = numero*i;
            console.log(numero + "X" + i + "=" + resultado);
        }
    }

    let valor = 2;
    tablaMultiplicar(valor);
``` 
