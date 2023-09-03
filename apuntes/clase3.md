# Clase 3 - 31/8/2023

## Introducción

"Hasta ahora se habló del proceso software, de sus etapas y sus participantes. También de la importancia de detectar los errores lo antes posible. La última clase se abordó sobre qué es la gestión de requisitos y nos metimos en algunos modelos que describen la ingeniería de requisitos ( Sommerville y Wiegers )" - Profesor

## Criterios para _clasificar_ a los requisitos

### Por proceso

Al ser un proceso existe una **entrada** y **salida**.

La entrada de la ingeniería de requisitos son los requisitos/requerimientos del cliente. Son las manifestaciones de lo que _desea_ el cliente.

La salida son los requisitos/requerimientos del sistema. Nosotros aplicaremos técnicas y estrategias para producir ese output. Una especificación orientado a lo técnico (precisa y detallada) de lo que el sistema debe hacer y sus límites que pueda tener.

    Para poder satisfacer los deseos del cliente lo haremos a través de una máquina que llamaremos sistema informático. Le va a permitir al cliente solucionar su problema o aprovechar una oportunidad que se le presente.

_El cliente generalmente no sabe lo que quiere y quizás el piensa que quiere algo y en realidad no lo necesita_.

### Por nivel de detalle

Cuando los requisitos están expresados en detalle serán llamados **requisitos de Bajo nivel**. En cambio cuando sean más abstractos y _por arriba_ serán **requisitos de Alto nivel**.

Alto nivel: ambigua, incompleta, imprecisa, la extensión es breve, no hay forma estructurada. Para qué sirven? tienen un objetivo: permitir de una forma rápida y sencilla introducirnos a la funcionalidad o la restricción que se necesita. Uno se hace una idea de lo que se trata el requisito.

Bajo nivel: sumamente detallado, documentación exhaustiva, puede tener un carácter contractual, es decir, que puede servir para el desarrollador y el cliente para saber si los requisitos están cubiertos o no.

Ejemplo profe: **SUBE**.

        Alto nivel: El sistema único de boleto electrónico sube deberá permitir abonar el costo de un viaje en un transporte público de pasajeros. (podrían ser mas cosas pero eso es lo ESENCIAL).

        Bajo nivel: Aquí estarán los datos que participan en el proceso, la funcionalidad, con ciertas restricciones que surjan. Abordará las alternativas, es decir, que pasa en un caso y en otro... y ciertos escenarios. Lenguaje estructurado y semiestructurado. No es una entrada sencilla, sino que busca brindar la mayor presición posible. Evita ambiguedades e imprecisiones. No es lo mismo un transporte ÓMNIBUS que un TREN. Considerar información como el número de tarjeta, el saldo disponible, el monto... El registro de la transacción... Casos que no se pueda abonar el viaje... Tener en cuenta descuentos por múltiples viajes en un rango horario...

Generalmente obtenemos del cliente los requisitos de alto nivel y nuestro trabajo será generar los de bajo nivel.

### Por funcionales / no funcionales

Un **requisito funcional** es algo que el sistema hace ó que _debe proveer_.

Ejemplo Sistema Horno/Microondas: El sistema deberá permitir calentar la comida. El sistema deberá permitir conocer la hora. Funcionalidad calentar, autolimpiar...

Ejemplo Sistema SUBE: Realizar una carga de saldo, obtener el listado personal de viajes. Deberá permitir pagar _refrigerios_ en máquinas expendedoras.

Es bueno recordar que... **un requisito es la formulación y exigencia de esa capacidad**.

Un **requisito no funcional** agrega información a la funcionalidad descrita anteriormente ó del sistema en general. Caracterizan/Condicionan a los requisitos funcionales ó al sistema completo. Un requisito no funcional puede detallar bajo qué circunstancias ó condiciones se va a desempeñar algo.

Ejemplo Ama de llaves: Que se encargue de resolver la limpieza de mi casa, efectuar los pedidos a los proveedores de almacén, abonar las cuentas de los impuestos... todo eso lo puede realizar mediante la acción de un ser humano ó a través de un sistema robótico que trabaja las 24hs... **digo el cómo se hace**.

    Importante destacar nuevamente que el requisito no funcional puede tratar acerca de un requisito funcional ó sobre el sistema general.

---

## Glosario

> AQNC: (Algo que no conozco) Explicación de que es ese algo.

## Bibliografia

- [PPT de MIeL](https://miel.unlam.edu.ar/path-a-la-ppt-de-miel-en-cuestion)
- [Otro link](https://www.otro-link-clave.com/)
