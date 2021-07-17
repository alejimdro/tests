## There are many ways to contribute to the Visual Studio Code project: logging bugs, submitting pull requests, reporting issues, and creating suggestions.

# Cómo convertirse en colaborador y enviar su propio código

Además de contribuir a escribir código, existen muchas otras maneras de colaborar, como, por ejemplo, registrando errores, presentando solicitudes de extracción, informando de problemas `y/o` creando sugerencias. El objetivo de este documento es ofrecer una visión general de cómo puede participar.

## Directrices de contribución

Nos gustaría contar con su colaboración para mejorar este proyecto. `A fin de` ayudarnos a mantener la alta calidad del mismo, solicitamos que las contribuciones se adhieran a las siguientes directrices:

- **Explique por qué `hace/está haciendo` un cambio**. Aunque parezca evidente, dedique una o dos líneas a explicarnos por qué debe ser tomado en cuenta su cambio o adición. Resulta especialmente útil indicar por qué este cambio debe ser aplicado y cómo beneficia a los usuarios.

- **Considere el alcance de su cambio**. Si su cambio es específico para un determinado comportamiento o funcionalidad, asegúrese entonces de que dicho cambio es razonablemente aplicable y `que` se realiza en la plantilla reservada para tal fin`es`.


Si su cambio es específico para un determinado comportamiento o funcionalidad, asegúrese entonces de que dicho cambio es razonablemente aplicable y que se realiza en la plantilla adecuada según su tipo.

Si su cambio es específico para un determinado comportamiento o funcionalidad, asegúrese entonces de que dicho cambio es razonablemente aplicable y que, según su tipo, se realiza en la plantilla adecuada.



Si su cambio es específico para un determinado comportamiento o funcionalidad, asegúrese entonces de que dicho cambio es razonablemente aplicable y se realiza en la plantilla reservada para tal fin.

@RAEinforma #dudaRAE ¿Podrían recomendarme una de las frases adjuntas? Por otro lado, para hacer referencia al tipo de cambio, ¿sería más recomendable la forma «según su tipo» o «según su fin»? ¿Son correctas estas construcciones o sería más recomendable usar «en la plantilla más adecuada»? Saludos cordiales

a) Si su cambio es específico para un determinado comportamiento o funcionalidad, asegúrese entonces de que dicho cambio es razonablemente aplicable y que se realiza en la plantilla adecuada según su tipo.

b) Si su cambio es específico para un determinado comportamiento o funcionalidad, asegúrese entonces de que dicho cambio es razonablemente aplicable y que, según su tipo, se realiza en la plantilla adecuada.

a) Si su cambio es específico para un determinado comportamiento o funcionalidad, asegúrese entonces de que dicho cambio es razonablemente aplicable y se realiza en la plantilla reservada según su fin.


- **Modifique solamente `*una plantilla*` por solicitud de extracción**. Esto contribuye a mantener las solicitudes de extracción y los comentarios centrados en un cambio o adición `específicos/concretos`.

En general, cuanto más pueda ayudarnos a entender el cambio que está haciendo, más probable será que aceptemos su contribución rápidamente.

## Informar de problemas y solicitar funciones

¿Ha identificado un problema reproducible? ¿Tiene una petición de funcionalidad? ¡Su contribución es bienvenida! A continuación le indicamos cómo puede hacer que la notificación de su problema o sugerencia sea lo más eficaz posible.

### Búsqueda de problemas y solicitudes de funciones existentes

Antes de crear una nueva notificación, por favor, haga una búsqueda en las [notificaciones abiertas](https://github.com/microsoft/vscode/issues) para comprobar si la notificación o solicitud de función ya ha sido presentada.

Asegúrese de revisar las [solicitudes de funciones más populares](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc).

Si descubre que su notificación ya existe, haga los comentarios pertinentes y añada su [reacción](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments). Por favor, utilice una reacción en lugar de un comentario «+1»:

* 👍 - voto positivo
* 👎 - voto negativo

Si no encuentra una notificación existente que describa su problema o función, cree una `nueva` notificación siguiendo las directrices que se indican a continuación.

### Redacción adecuada de informes de problemas y solicitudes de funciones

1. Presente una única notificación por problema y solicitud de función. No enumere varios errores o solicitudes de funciones en la misma notificación.

3. No añada su notificación como un comentario a una notificación ya existente, a menos que se trate de una entrada idéntica. Muchas notificaciones parecen similares, pero tienen causas diferentes.

0. Si la nueva notificación está relacionada con otro problema o solicitud de extracción, indique su URL completa o el número de dicho problema o solicitud de extracción precedido del símbolo de almohadilla (#); por ejemplo, «Notificación relacionada: #987654».

2. Proporcione una descripción clara del problema y explique el impacto concreto que tiene este en los usuarios. Detalle lo que falta específicamente e indique lo que no está actualizado, es incorrecto o es preciso mejorar.

> **Nota:** Cuanta más información pueda proporcionar, más probable será que alguien consiga reproducir el problema y encontrar una solución.

0. Limite el alcance de un problema determinado a una unidad de trabajo razonable. En el caso de los problemas de gran alcance, divida dichos problemas en otros más pequeños. Por ejemplo, «Actualizar la documentación de contribución» es demasiado amplio, [pero] «Añadir detalles al apartado “Directrices de contribución”» es lo suficientemente específico como para ser procesable.

0. Respete el [Código de Conducta](./CODE_OF_CONDUCT.md) y las [Normas de contribución](./CONTRIBUTING.md). Recuerde que es responsable de sus comentarios y del alcance de sus acciones. Todas sus actuaciones son relevantes y pueden tener importantes consecuencias tanto dentro como fuera de la comunidad. Sea respetuoso al hacer comentarios acerca de otros colaboradores o sus contribuciones. Por ejemplo, «La documentación es horrible» no es un comentario útil ni cortés.

Por favor, incluya lo siguiente en cada informe de problemas:

* Pasos necesarios para reproducir el problema de forma fiable

* Resultados reales y esperados

* Imágenes, animaciones o un enlace a un vídeo que muestre el problema

* Un fragmento de código que demuestre el problema o un enlace a un repositorio de código que los desarrolladores puedan consultar con facilidad para recrear dicho problema localmente

  > **Nota:** Dado que los desarrolladores necesitan copiar y pegar el fragmento de código, incluir `este fragmento de código` como archivo multimedia (por ejemplo, .gif) no es suficiente.

### Lista de verificación final

Por favor, tenga en cuenta lo siguiente a la hora de notificar un problema:

* [ ] Busque en el repositorio de problemas para asegurarse de que informa de un problema nuevo

* [ ] Exponga el problema de forma clara y rigurosa/precisa/fehaciente

* [ ] Simplifique su código en torno a la `incidencia` para aislar mejor el problema

Es posible que los desarrolladores no puedan reproducir el problema de inmediato; en ese caso, solicitarán más información al respecto.

# Agradecimientos

Sus contribuciones al código abierto, grandes o pequeñas, hacen posibles valiosos proyectos como este. Gracias por tomarse el tiempo de contribuir.
