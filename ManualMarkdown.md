# Manual de Markdown
Este manual nos guiará en el uso de la **sintáxis** de *MarkDown* <br>
Los títulos en el formato de markdown Funcionan con el uso de "#", acumulándose llegando hasta un máximo de 6 títulos o encabezados ("######")<br>
###### (Siendo este el **último y __menor__** título/encabezado.)
## Clase de cambios aplicables al texto:

- Para realizar saltos de línea se usa *"(br, pero entre mayor y menor qué.)"*<br>
- Para establecer un texto o tramo de texto en **negrita** se rodea con dos astericos "(**)" <br>
- Para hacerlo *cursiva* solo con uno "(*)"

## Listas:
Existen dos tipos de listas:
1. Ordenadas
  - Las listas ordenadas es establecen al iniciar el párrafo con un número, un punto y un espacio: "(1. )"
2. Sin ordenar
 - Las listas sin ordenar se establecen al iniciar el párrafo con un guión: "(-)"

 ## Links:
  [Tux, Linux Mascot](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/1200px-Tux.svg.png "Tux") <br>
  Para introducir links seguimos la siguiente sintáxis: "[Entre corchetes va el texto alternativo](Entre paréntesis la URL de la imagen "Y un título para esta")<br>
  Y para introducir una imagen<br>
  ![Tux, the Linux mascot](/images.jpg)<br>
  La sintaxis es: "!" comenzar con un signo de exclamación, Proseguimos con el texto alternativo entre corchetes "[AltText]" y entre paréntesis elegimos la ruta con una barra "/", y el nombre del archivo.
  Para introducir código hay que ponerlo entre tildes.<br>
  Aquí un ejemplo de `código`:<br>
       
        for (int i = 0; i < 8; i++) {
            for (int j = 0; j < 8; j++) {
                if ((i + j) % 2 == 0) {
                    matrix[i][j] = 'B';
                } else {
                    matrix[i][j] = 'N';
                }
            }//Cierre for J

        }//cierre for I
        for (int i = 0; i < 8; i++) {
            for (int j = 0; j < 8; j++) {
                System.out.print(matrix[i][j] + " "); //A este sout se le quita el Ln para que no haga el lane jump
            }
            System.out.println(); //Este sout hace el salto de línea
        }

    }//cierre main`
## Citas:
GNU/[Linux](https://es.wikipedia.org/wiki/GNU/Linux "Linux Wikipedia") (pronunciado oficialmente como ñu linux o también ge-ene-u linux en español), 
es una familia de sistemas operativos tipo Unix compuesto por software libre y de código abierto.<br>
Justo como los enlaces, las citas sigue una sixtánsis muy similar a los enlaces, en este caso entre corchetes elegiremos el texto a enlazar "[Linux]", seguido de unos paréntesis con el enlace y una pequeña anotación: "(https://es.wikipedia.org/wiki/GNU/Linux "Linux Wikipedia")".
## Tablas:
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Fila 1    | Fila 2    | Fila 3    |
| Fila 1    | Fila 2    | Fila 3    |
<br>
Para la realización de tablas, en MarkDown resulta bastante más confuso, ya que con se redacta lo más cercano a una tabla, en este caso comenzando con "|" para comenzar las columnas y separarlas las unas de las otras, y para separar filas, concretamente la primera fila de las demás (Pues para las demás filas no es necesario hacerlo) (Usando el "|" para continuar separando) se usan guiones "-".
<br>

## Bibliografía
https://denshub.com/es/howto-create-table-markdown/
