Custom Hooks

useCounter:

Contador que recibe como parámetro un valor iniciar. Si no recibe nada toma el valor de 10 por defecto.
Devuelve 4 elementos: el contador y tres funciones para manejar el contador.
increment: aumenta el contador en 1
decrement: disminuye el contador en 1
reset: reinicia el contador a su valor inicial

useFetch:

Recibe informacion de una peticion que realiza a una url que recibe como parametro
Devuelve un state compuesto el siguiente objeto:
{ 
    data: Conjunto de datos que trae de la petición a la url (Valor por defecto: null)
    loading: Valor booleano para determinar si realizó la petición o no (Valor por defecto: true)
    error: Guarda información del error. Por el momento solo toma el valor de un array (Valor po defecto: null)
}

useForm:

Hook para manejar formularios.
handleInputChange permite escribir en los inputs 
cleanInput permite limpiar los inputs