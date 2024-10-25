# Manual de Markdown
Este manual nos guiará en el uso de la **sintáxis** de: "*MarkDown*" <br>
# Índice:
## 1. Títulos y encabezados:
## 2. Formación de párrafos.
## 3. Énfasis al texto
## 4. Listas
## 5. Links
## 6. Imágenes
## 7. Citas de código
## 8. Tablas:
## 9. Bibliografía

<br><br>
### 1. Títulos y encabezados:
#### ¿Cómo se escriben?
Los títulos en el formato de markdown Funcionan con el uso de `#`, acumulándose llegando hasta un máximo de 6 títulos o encabezados `######`.<br> 
Otra manera<sup>1</sup> de formar encabezados, es escribir debajo del texto que queremos poner como título, uno o varios iguales para un encabeazdo de 'nivel 1': "`=`", y uno o varios guiones para un encabezado de 'nivel 2': "`-`".<br>
#### Errores a evitar:
Para redactar sin problemas encabezados o títulos, la almohadilla o *sharp* debe estar separado del texto a encabezar por un espacio. Estando juntos no contará como encabezado.
#### Ejemplo:
#Este encabezado está mal redactado.
# Este es el primer encabezo o título, usando solo una "#" (O usando el método alternativo véase el superíndice 1.).
###### Este es el último título/encabezado usando 6 "######"

<br><br>
## 2. Formación de párrafos.
<p>La formación de párrafos en markdown funciona exactamente igual que en html, usando las siguientes etiquetas:</p>

Usando la etiqueta: `<p>` de apertura y la etiqueta `</p>` de cierre.

<br><br>
## 3. Énfasis al texto:
- Para realizar saltos de línea se usa *`<br>`*"<br>
- Para establecer una palabra, texto o fragmento de texto en **negrita** se rodea con cuatro astericos, dos antes del fragmento de texto a poner en negrita., y dos al final *"(**)"* <br>
- Para hacerlo *cursiva* solo con dos, de nuevo uno antes del fragmento de texto, y otro al final de este ("*")
<br><br>
### Ejemplo
`**Este texto está en negrita**` **Este texto está en negrita** <br>
`*Este texto está en cursiva*` *Este texto está en cursiva*

<br><br>
## 4. Listas:
Existen dos tipos de listas en markdown:
1. Ordenadas
  - Las listas ordenadas es establecen al iniciar el párrafo con un número, un punto y un espacio: "(1. )"
2. Sin ordenar
 - Las listas sin ordenar se establecen al iniciar el párrafo con un guión: "(-)"

<br><br>
 ## 5. Links:
### - Ejemplo:
 ·GNU/[Linux](https://es.wikipedia.org/wiki/GNU/Linux "Linux Wikipedia") (pronunciado oficialmente como ñu linux o también ge-ene-u linux en español), 
es una familia de sistemas operativos tipo Unix compuesto por software libre y de código abierto."<br>
  Para introducir links seguimos la siguiente sintáxis: `[Entre corchetes va el texto alternativo](Entre paréntesis la URL "Y un pequeño texto")` <br>
### - Ejemplo de redacción:
  `[Linux](https://es.wikipedia.org/wiki/GNU/Linux "Linux Wikipedia")`
### - Explicación
En este caso entre corchetes elegiremos el texto a enlazar "[Linux]", seguido de unos paréntesis con el enlace y una pequeña anotación: "(https://es.wikipedia.org/wiki/GNU/Linux "Linux Wikipedia")".

<br><br>
## 6. Imágenes:
  Para introducir una imagen seguimos una sintaxis muy similar a la que usamos para introducir links, pero en este caso añadimos un signo de exclamación.<br>
  
### - Ejemplo de imagen.
  ![Tux, the Linux mascot](/images.jpg)<br>
  
### - Sintaxis:
  La sintaxis es: "!" comenzar con un signo de exclamación, Proseguimos con el texto alternativo entre corchetes "[AltText]" y entre paréntesis elegimos la ruta con una barra "/", y el nombre del archivo. <br>
  La sintáxis del la imagen anterior es: <br>
  `![Tux, the Linux mascot](/images.jpg)`

  <br><br>
## 7. Cita de código:

### - Sintaxis:
  Para introducir código hay que ponerlo entre tildes invertidas, solo dos tildes invertidas (Una al inicio y otra al final del tramo o palabra a citar como texto y en caso de citar un bloque, 6 tildes invertidas 3 antes del bloque de texto y otras 3 al final de este.)..<br>
  
###  - Ejemplo:

  Aquí un ejemplo de `código`:<br>
  
  ```
>public class EjemploAjedrezMatrizChar {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        char[][] matrix = new char[8][8];

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

    }//cierre main
}//cierre class
```

<br><br>
## 8. Tablas:
###  - Ejemplo:
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Fila 1    | Fila 2    | Fila 3    |
| Fila 1    | Fila 2    | Fila 3    |
<br>
### - Ejemplo de redacción:

´´´
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Fila 1    | Fila 2    | Fila 3    |
| Fila 1    | Fila 2    | Fila 3    |
´´´

### - Explicación
Para la realización de tablas, en MarkDown resulta bastante más confuso, ya que con se redacta lo más cercano a una tabla, en este caso comenzando con "|" para comenzar las columnas y separarlas las unas de las otras, y para separar filas, concretamente la primera fila de las demás (Pues para las demás filas no es necesario hacerlo) (Usando el "|" para continuar separando) se usan guiones "-".

<br><br>
## 9. Bibliografía
https://denshub.com/es/howto-create-table-markdown/
