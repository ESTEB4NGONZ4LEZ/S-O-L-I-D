# S-O-L-I-D

Este es un proyecto de Vanilla TypeScript en Vite, para trabajar los ejercicios del curso sobre Principios SOLID y CleanCode.

## Deuda Tecnica 

La deuda tecnica es la falta de calidad en el codigo que escribimos, esto va a repercutir en costos futuros usualmente en costos economicos y esos costos economicos son producto de:

- Tiempo en realizar mantenimiento.
- Tiempo en refactorizar el codigo.
- Tiempo en comprender el codigo.
- Tiempo adicional en la transferencia del codigo.

Esquema de la deuda tecnica de Martin Fowler:

- Imprudente: Tipo de deuda en el cual el desarrollador actua de forma consiente y de forma imprudente, suele llevar a un proyecto de mala calidad y es poco tolerante al cambio.

- Inadvertida: Se genera por la falta de experiencia.

- Prudente: Es la deuda en la que sabemos que tenemos esa deuda

- Cuando iniciamos un proyecto y no sabemos como va el desarrollo, y con el paso del tiempo vamos comprendiendo y dando calidad al mismo.

COMO SE PAGA UNA DEUDA TECNICA?

### Refactorizacion 

Es el proceso que tiene como objetivo mejorar el codigo sin altenar su comportamiento para que sea mas entendible y tolerante a cambios.

Cuando se quiere hacer una refactorizacion fuerte, para que tenga el objetivo esperado, es imprecindible que el codigo que estamos refactorizando tenga pruebas automaticas.

### Funciones 

- La simplicidad es fundamental.
- Funciones de tamano reducido.
- Funciones de una linea sin causar complejidad innecesaria.
- Menos de 20 linead de codigo .
- Evitar el uso del else.
- Priorizar el uso de la condicional ternaria.

### Principio DRY

- Evitar duplicidad en el codigo.
- Simplifica las pruebas.
- Ayuda a centralizar procesos.
- Aplicar el principio DRY, lleva a refactorizar.
