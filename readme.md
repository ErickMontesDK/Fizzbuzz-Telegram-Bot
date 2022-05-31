# Fizzbuzz Telegram Bot

## Resumen
El bot consulta a una API, cuyo servidor se tiene que ejecutar localmente. La API consulta un archivo JSON que posee una lista de alumnos registrados a una mission y poseen un score.<br>
Si le envias una palabra al bot, el te regresa la lista de alumnos que estan registrados en la mission con esa palabra.
Si le envias un numero, te regresa una clave de validación. 

## Instalación y uso
>1) Clonar el repo al ordenador<br><code>git clone https://github.com/ErickMontesDK/VIsual-Thinking-Api </code>
>2) Instalar el paquete y dependencias en la carpeta de proyecto <br><code>npm install </code>
>3) Ya instalado, ejecutamos el bot y el servidor mediante el codigo<br><code>npm run bot</code>
>4) Accedemos al bot mediante la siguiente url<br><code>https://t.me/ErickR2D2MontesBot</code>
<hr>

## Consulta
Se puede enviar cualquiera de los siguiente mensajes.
>1) Palabra de mission: Si se envia una palabra, el bot regresará la lista de alumnos cuya mission sea esa palabra. 
Las dos missions que pueden tener los alumnos es <b>"node" o "java"</b>. Cualquier otra palabra no tendra resultados ya que no hay alumnos con una mission distinta.
>2) Número de score: Al enviarle un numero, el bot lo detecta como un score de un alumno, y te regresa una clave de validación dependiendo del valor del score. 
> * Si es múltiplo de 3, regresa clave <b>FIZZ</b>
> * Si es múltiplo de 5, regresa clave <b>BUZZ</b>
> * Si es múltiplo de 3 y 5, regresa clave <b>FIZZBUZZ</b>

