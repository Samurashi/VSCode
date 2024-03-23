Wena Choro que pasa
el nombre de la carpeta "src" es un nombre usado por convencion para guardar el codigo fuente de mi app dentro de esta carpeta

Ejemplo de Lorem Lipsum
    "But I must explain to you how all this mistaken idea of denouncing pleasure and praising nice was born and I will give you a 
    complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human
    happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to
    pursue pleasure rationally encounter consequences that are extremely painful. Nor again is there anyone who loves or pursues or 
    desires to obtain nice of itself, because it is nice, but because occasionally circumstances occur in which toil and nice can 
    procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious physical exercise, except to 
    obtain some advantage from it? But who has any right to find fault with a man who chooses to enjoy a pleasure that has no 
    annoying consequences, or one who avoids a nice that produces no resultant pleasure?"

Lineas & Columnas
La Sintaxis Sera:
    :'Numero de Linea','Numero de Columna'
En la Barrita Superior Escribir:
    ":5,10" -> Linea 5, Columna 10

Elementos de la Barra Inferior (Status Bar)
    CRLF (Carriage Return Line Feed): Configuracion de Final de Linea, Especial de Windows
        Linux/iOS -> LF (Line Feed)

    UTF: Unicode Transformation Format, Codificacion: Es como Veremos los Caracteres en Pantalla Dependiendo del Valor que Tenga Asociado en la Maquina
    Caracteres de Accion/Vacios: Las Nuevas Lineas, Cada Sistema Puede Elegir el Caracter que Quieran para Reprentar en Binario el Espacio de una Nueva Linea, esto Viene del Valor en Binario que Representan a las Letras en UTF Cuando se Codifican
    Para Representar una Nueva Linea, Windows Ocupa dos Tipos: CR & LF 
    Linux y IOS Ocupan Solo LF 

    PROBLEMA: si alguine hace un codigo en Mac y yo en Windows podriamos llegar a tener problemas por el estilo de Config de Linea que esta decidido en nuestros sistemas y podriamos tirar errores en nuestro codigos si llegarn a ser compartidos mutuamente entre los dos sistemas operativos
    SOLUCION: GitHub hace la transformacion

    Spaces: Cantidad de Espacios que Tengo Actualmente en mi Identacion 