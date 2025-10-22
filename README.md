<!DOCTYPE html>
<html lang="en">
<head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        </head>
        <body>
    
        <style>
     table th,td { border: 1px solid black; border-collapse: collapse;


     }



        </style>
     <table>
     <!--                  <form>, <h1>, <p> 
                                 -->
        <tr>
            <th>
     <h1>Encabezado principal</h1>
     <form>
        <input type="search" placeholder="Barra de navegacion" style="width: 90%;">
        <button type="submit">buscar</button>
     </form>
   
        <H2>Contenido Principal</H2>
     <p>Este es el contenido de la pagina</p>


         <!--         Listas                     -->


        <H2>lista Ordenada</H2>
        <ol>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
        <li>Elemento 3</li>

    </ol>
    <h2>Enlances</h2>
    <p> Este es un <a href="https://www.google.com/?hl=es">Enlace absoluto a Google</a></p>
    <p> Este es un enlace Relativo a <a href="ciudadeslistas.html">Otra pagina del proyecto</a></p>


        <!--                   Table                 -->




        <h2>Tabla de Ejemplo</h2>
       <table>
            <tr>
             <th colspan="2">   Encabezado de tabala</th>
        
            </tr>
            <tr>
                <td>
                    Fila 1, columna 1
                </td>
                <td>
                    Fila 1, Columna 2
                </td>
            </tr>
            <tr>
                <td rowspan="2">
                    Fila 2-3, Columna 2
                </td>
                <td> Fila 2, columna 2</td>
                

            </tr>
            <tr>
                <td>Fila 3 columna 2 </td>
            </tr>





        </table>
     <h2>Formularios</h2>

        <form>

      <label for="fname">first name:
     </label>    

       <input type="text" id="fname" name="fname" placeholder="name"
        ><br>
        <br><label for="psw">Password</label>
        <input type="password" id="psw" name="psw"
        placeholder=" introduce tu contraseña"><br><br>
        
        <label for="com">Comentario</label>
        <br>
        <textarea id="com" name="com"></textarea>
        <br>
        <label for="opc">Suscribirse</label>
        <input type="checkbox" id="opc" name="opc">
        <br>
        <button>boton generico</button>





         
        </th>

        </form>
        </tr>
        </table>
</body>
<div>




     
        
</div>
</html>
