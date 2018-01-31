# **FUNCTION-SCOPE-JS**

#### Funciones globales: 1
Es una función global en relación al contexto de ejecución del document y con respecto al contexto de ejecución window es una función local.
* funcion anónima:


```js  
    $(document).ready(function() {};
```

#### Variables globales: N° -> 6

En relación al contexto de ejecución del document, siendo LOCALES para el contexto de ejecución global del window.
```js
* $inputCard
* $inputMonth
* $inputYear
* $buttonNext
* regexOnlyNumbers
* labelErrorOrSuccessMessages
```
#### Funciones locales: N° -> 5
```js
* function activeButton() {}
* function desactiveButton() {}
* function longitud(input) {}
* function soloNumeros(input) {}
* function isValidCreditCar(numberCard){}
```
#### Funciones callback: N° -> 0

#### Expresions statement: N° -> 5
```js
  activeButton();
  desactiveButton();
  longitud(input);
  soloNumeros(input);
  isValidCreditCard(numberCard);
```
#### Clousure: N° ->

#### Scope: N° -> 17

```js
* $(document).ready(function() {};
* $inputCard.on('input', function() {}
* function activeButton() {}
* function desactiveButton() {}
* function longitud(input) {}
* if (input.trim().length === 16) {}
* function soloNumeros(input) {}
* if (regex.test(input)) {}
* function isValidCreditCard(numberCard) {}
* if (creditCardNumber !== undefined) {}
* for (var index = creditCardNumber.length - 1; index >= 0; index--) {}
* for (var index = 1; index < arr.length; index = index + 2) {}
* if (arr[index] >= 10) {
* for (var index = 0; index < arr.length; index++) {}
* if (sumaTotal % 10 === 0) {}
```
## Contextos de ejecucion

#### Funciones que forman parte de la PILA:

#### Funciones que forman parte de la COLA: N° -> 2

```js
activeButton();
desactiveButton();
```
