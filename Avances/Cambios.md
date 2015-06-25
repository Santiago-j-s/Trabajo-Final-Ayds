* StarUML me había trolleado con el diagrama de clases, lo tuve que hacer de nuevo, aparecían algunas etiquetas que no se podían borrar ni mover.

* Agregué algunas clases, así como atributos que estoy casi seguro de que quedarán finalmente. También cambie algunas relaciones por otras que parecieran tener más sentido.

* No pude conseguir hacer los diagramas de DI de Elegir Medio de Pago y Realizar Pago. Creo que ambos podrían ir como casos de uso separados (de hecho Elegir Medio de Pago ya lo tenemos como CU aparte). Tengo problemas similares a los que surgieron con Realizar Pago y tampoco encuentro la forma de realizarlos con métodos en las clases que tenemos. En la hoja el controlador setea el medio de pago en el encargo y este a su vez lo setea en la factura, en nuestro modelo de clases deberíamos como mínimo pasar por la venta ya que ella es quien emite la factura. Lo mismo para Realizar Pago y la verdad es que no estoy seguro de como hacerlos.

* Mira en StarUML en export la opción htmldocs, esta muy buena.

* Los diagramas de interacción tienen que ir dentro de colaboraciones (se ven como elipses similares a los casos de uso pero con línea punteada), uno por colaboración. Si pones dos diagramas de interacción en un mismo CU sin hacerlo así te encontrarás con todos los objetos borrados, es sumamente divertido, logre salvarlo gracias a Git xD.

* Aprendí como hacer los diagramas de comunicación a partir de los de interacción, solo tenemos que hacer los de interacción y luego es fácil el resto :P.

* Vi el Realizar Pedido de Insumos y no esta mal, creo que falta detalle en el paso 2 y tengo dudas con la extensión, si se hace de la forma tradicional no pertenece a nuestro sistema.

* Subi a GDrive el .mdj actualizado.

* Voy a dormir unas 5 o 6 horas, estimo que entre las 12 y las 14 despierto.

* Suerte :P.
