# Taller03-SOLID
1) Claro, debreria crearse la clase postre y poner especial enfasis en que cumpla el principio de abierto-cerrado.
2) No es necesaria, seria mejor crear un metodo dentro la clase postre para anadir o remover el adrezo, viola segregacion de interfaz
3) En el proyecto deberia haber un paquete destinado ha facturacion y no que cada clase tenga su calcular precio o showprecio, esto viola el principio de responsabilidad unica
4)Esta de aqui violaba el principio de inversion de dependencias ya que al cambiar de estatico a abstracto nos permite eliminar la dependencia al detalle del tipo de aderezo 
5) Se podria poner dentro de la clase pastel, el tipo de leche con el que se hace como un constructor y hacer uno con descremada y entera y en el caso de la descremada lance una excepcion

Eduart Macias y Xavier Lopez
