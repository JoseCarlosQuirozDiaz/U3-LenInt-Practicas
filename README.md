# U3-LenInt-Practicas

Practica 1
El programa muestra un mensaje de inicio, después llama al procedimiento mensajeAviso dos veces, el cual imprime en pantalla el mensaje "Estoy dentro del procedimiento". Posteriormente, asigna valores a los registros EAX y finalmente muestra el mensaje "Fin del programa" antes de terminar su ejecución.

Practica 2
El programa solicita al usuario ingresar una cadena de texto y utiliza el procedimiento ValidarCadena para comprobar si está vacía o contiene algún carácter. El procedimiento revisa el primer byte de la cadena y devuelve 0 si está vacía o 1 si tiene contenido mediante el registro EAX. Finalmente, muestra el resultado correspondiente en pantalla.

Practica 5
El programa utiliza una macro llamada MostrarMensaje para imprimir textos en pantalla. Primero muestra el mensaje de bienvenida al sistema de inventario y después muestra un mensaje de despedida. La macro utiliza WriteString para escribir el texto y Crlf para realizar un salto de línea. Esto permite reutilizar el mismo código sin repetir instrucciones.