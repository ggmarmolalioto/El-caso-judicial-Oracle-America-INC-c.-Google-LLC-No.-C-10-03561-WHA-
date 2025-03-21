# CAPITULO VIII
 
# RECURSO DE APELACIÓN (PETICIÓN I DE WRIT OF CERTIORARI) ANTE LA CORTE SUPREMA DE JUSTICIA DE EE.UU. INTERPUESTO POR GOOGLE CONTRA LA SENTENCIA DEL TRIBUNAL DE APELACIONES DEL CIRCUITO FEDERAL

Contra esta sentencia del Tribunal de Apelaciones del Circuito Federal que determinó que el código fuente declarado y la estructura, secuencia y organización de los paquetes de las API de JAVA era protegible bajo el sistema de derecho de autor de EE.UU., Google con fecha 6 de octubre del 2014 presentó una Petición I de Writ of Certiorari [91] ante la Corte Suprema de Justicia de EE.UU. (SCOTUS). 

# ARGUMENTOS DE GOOGLE CONTRA LA SENTENCIA I DEL TRIBUNAL DE APELACIONES DEL CIRCUITO FEDERAL 

     Google sostuvo que la decisión del Tribunal de Apelaciones del Circuito Federal del 9 de mayo de 2014 era contraria a derecho, ello conforme a lo dispuesto en el artículo 102, inciso b), del Título 17 USC. 
     
     Afirma Google que el “código fuente declarado” o “encabezado del método” (en inglés “method header”) constituye un “método de operación o un método para operar” y, por ende, se encuentra excluido de toda protección bajo la ley de derechos de autor de EE.UU. 
     
     Al hacer Sun Microsystems disponible el lenguaje de programación Java sin restricciones de ningún tipo, Sun Microsystems buscaba atraer a la mayor cantidad de personas posibles para construir una de las redes más grande del mundo. 
     
     Mientras Sun Microsystems alentaba a los programadores a aprender y utilizar el lenguaje de programación Java, promocionaba sus programas pre-escritos (la librería de software estándar de Java). 
     
     Sun Microsystems tuvo éxito en llevar a una generación entera de programadores a la comunidad de Java. 
     Millones de programadores invirtieron tiempo y esfuerzo en aprender el lenguaje de programación Java, convirtiendo a Java en uno de los lenguajes de programación más populares del mundo. 
     
     Así entonces los programadores tenían acceso al conjunto de programas pre-escritos por Sun Microsystems a través de las API de Java. 
     Las aplicaciones de programación de interface proveían acceso a esos miles de métodos de Java, ejecutando cada uno de ellos una función determinada, como las de en caso de darse dos números y elegir el mayor de ellos. 
     
     Así los métodos se agrupaban en clases, y las clases en paquetes. 
     
     El “código fuente” de cada método consiste en:
     
(i)	un “código fuente declarado” (en inglés “declaring source code”) o encabezado del método (en inglés “method header”) o simplemente declaración (en inglés “declaration”), y 

(ii)	un código fuente implementado (en inglés “implementing source code”) o cuerpo del método (en inglés “method body”). 
     El encabezado del método o declaración introduce el cuerpo del método y especifica los nombres, parámetros y funcionalidad de cada uno de los métodos (en inglés Java methods). 
     
     El cuerpo del método (en inglés “method body”) es un bloque de código que implementa el método instruyendo a una computadora de como ejecutar una determinada función, por ello se lo conoce como “código fuente implementado”.   
     
     Para poder hacer uso de los métodos, es decir, de la función que proporciona, los programadores no necesitan conocer el código fuente implementado, sólo deben conocer el “comando abreviado” (en inglés “shorthand command”) que causa que el código fuente implementado ejecute la función deseada, como la de elegir el mayor de dos números.
     
     De esta manera, los programadores utilizan estos comandos abreviados para operar el método (programas pre-escritos que conforman la librería de software estándar de Java). 
     Estos comandos abreviados poseen un formato especifico: 

**java.package.Class.method(input)**

     Cada “comando abreviado” deriva directamente del “código declarado” o encabezado de método”, que de igual forma que el comando abreviado, especifica el nombre del método, clase, paquete, y el input.  
     
     Así por ejemplo en “java.lang.Math.max(1.2)” se refiere a un método particular “max” que devuelve como resultado el mayor de dos números (1,2), localizado dentro de la clase “Math”, y esta a su vez localizada dentro del paquete “java.lang”. 
     
     Android es una de las plataformas para dispositivos móviles más populares del mundo. 
     
     En el segundo trimestre del año 2014, los fabricantes como Samsung, HTC, LG, y Lenovo vendieron más de 255 millones de teléfonos móviles inteligentes que utilizan la plataforma Android [92]. 
     
     La plataforma Android incluye unos 168 paquetes de métodos, y Google escribió o adquirió el código fuente implementado de esos paquetes (que conforman o integran la librería de software estándar de Android). 
     
     En el juicio en cuestión, no existe disputa entre las partes relacionadas a (i) el lenguaje de programación Java, y (ii) al código fuente implementado por Google. 
     
     Lo debatido y discutido entre las partes se centra sobre el uso que Google realiza sobre los mismos “headers” o encabezados o código fuente declarado de los métodos de cada uno de los 37 paquetes de la librería de software estándar de Android. 
     
     Métodos estos, que ejecutan funciones claves para los dispositivos de telefonía móvil. 
     
     Entonces, los programadores independientes crean aplicaciones para utilizar en dispositivos Android. 
     
     Teniendo en cuenta que los programadores conocen y usualmente prefieren desarrollar en el lenguaje de programación Java, Google concluyó que tales programadores querrían encontrar en la plataforma Android las mismas funcionalidades provistas por los 37 paquetes de Java, e invocables mediante el mismo sistema de nombres usados en Java.
     
     Por tanto, para que los “comandos abreviados” funcionaran en Android, Google tuvo que replicar exactamente los mismos “headers” o “encabezados de métodos” o “código fuente declarado” que el usado por Oracle en las API de Java, ya que cualquier cambio que Google hubiera introducido hubiera impedido que esos comandos abreviados funcionaran correctamente. 
     
     Es decir, como fuera sostenido por el Juez de la Corte de Distrito, en relación a estas líneas de código [fuente declarado] “Android y Java deben ser idénticas”.
     
     Como Google sólo replicó los encabezados de métodos o código fuente declarado, y, por otro lado, Google escribió su propio cuerpo del método o código implementado, sólo el 3% de las líneas de código son las mismas en los 37 paquetes en disputa.
     
     Entonces dicho todo lo anterior, y en relación al código fuente declarado, en su oportunidad la Corte de Distrito del Norte de California mencionó en su sentencia de mayo de 2012 que los “encabezados de métodos o código fuente declarado o simplemente declaraciones”, incluyendo sus nombres y su organización, conformaba un sistema o método de operación que se encuentra excluido de protección conforme a lo estipulado en el artículo 102 inciso b) del Título 17 del USC. 
     
     En efecto, dicho inciso b) del artículo 102 establece “En ningún caso la protección del derecho de autor sobre una obra original se extiende a cualquier idea, procedimiento, proceso, método para operar, concepto, principio, o descubrimiento, sin importar la forma en la cual sea [tal idea, o método, etc.] descripta, explicada, ilustrada, o incluida en la obra original. 
     
     Por tal razón, el Juez de la Corte de Distrito expresó que Google tenía derecho a escribir su propio código fuente implementado de las mismas funciones o métodos que se encuentran en las API de Java. 
     
     Así, se expresó que el derecho de autor de los EE.UU. no protege, y por ende no confiere derechos sobre una o todas las formas de implementar una función o especificación, sin importar que tan creativa pueda ser. 
     
     Teniendo en cuenta que el sistema del código fuente declarado o encabezados de métodos conforma una “estructura de comandos” para operar los programas pre-escritos, el Juez del Distrito concluyó que dicho sistema podría recibir tal vez protección a través del sistema de patentes de invención, pero no bajo el sistema de derechos de autor. 
     También el Juez de Distrito hace mención a la “compatibilidad”. 
     
     Antes de la fecha de la publicación de Android, y hasta su disponibilidad en el mercado, ya existían millones de líneas de código en Java las cuales necesariamente usaban el formato de comando java.package.Class.method() para llamar o invocar alguna o todas de las funciones de los 37 paquetes de Java en cuestión, y que claro, también necesariamente usaban los mismos nombres de la estructura de comandos. 
     
     Entonces, para que al menos parte de ese código escrito por los programadores independientes teniendo en cuenta el aprendizaje realizado en el lenguaje Java, pudiera ejecutarse en Android, Google estaba obligado a utilizar el mismo sistema de comandos de java.package.Class.method() con los mismos nombres y su misma taxonomía con las mismas funciones especificadas. 
     
     Como resultado de ello, Google replicó sólo aquello que era necesario para lograr un grado de “compatibilidad”, pero no más allá de ello, es decir, copió el código fuente declarado de las API de los 37 paquetes de Java y su estructura, secuencia y organización.
     
     Ahora bien, por otro lado, el Tribunal de Apelaciones del Circuito Federal sostuvo en cambio que el artículo 102 inciso b) no excluye a los sistemas o métodos de operación de la protección de los derechos de autor, y que, por lo tanto, todos los elementos originales de una obra están sujetos a la protección siempre y cuando, y en la medida que el autor de la obra original haya tenido múltiples formas de expresar esa idea. 
     
     Con lo cual, la protección de los derechos de autor se extiende a todos los elementos de una obra original, en este caso un programa de computación, incluyendo a los métodos de operación, en la medida de que el autor del programa de computación haya tenido al menos más de una forma de expresarlo. 
     
     Así el Tribunal de Apelaciones del Circuito Federal sostiene que el inciso b) del artículo 102 no extingue de la protección acordada a una forma particular de expresión de una idea por el mero hecho de que dicha idea esté expresada o incorporada en un método de operación. 
     
     La visión del Tribunal de Apelaciones del Circuito Federal es que la sección 102 inciso b) sirve solamente para codificar el principio del derecho de autor de EE.UU. de la dicotomía o división entre “idea” y “expresión [de idea]”, que expresa que la protección conferida por el derecho de autor se extiende sólo a la expresión de las ideas, pero no a las ideas en sí mismas. 
     
     Por lo tanto, afirma el Tribunal de Apelaciones del Circuito Federal que como Google podría haber escrito o construido sus propios paquetes si lo hubiese querido, y así haber escrito su correspondiente código fuente declarado o encabezados de métodos organizándolo y nombrándolo de diferentes formas, y aún, así lograr tener la misma funcionalidad, el artículo 102 inciso b) no impide la protección de derechos de autor a los paquetes de Java. 
     
     Es decir, que la interpretación del artículo 102, inciso a) [93] y b) debe hacerse de manera colectiva, conjunta y no de forma excluyente. 
     
     Google sostiene que este razonamiento del Tribunal de Apelaciones del Circuito Federal es absolutamente incorrecto, contrario al derecho de EE.UU., y a la historia legislativa de los incisos a) y b) del artículo 102 del Título 17 del USC. 
     
     Bajo el artículo 102 inciso a) la autoría de una obra original es “generalmente” protegible y, bajo el inciso b), que va sobre lo “específico”, se establece que en ningún caso la protección de la autoría sobre las obras originales se extiende a los sistemas, métodos para operar, etc., sin importar la forma en la cual estos [los métodos, sistemas, etc.] sean descriptos, explicados, ilustrados o incorporados en la obra. 
     
     No hay nada de ambiguo o de poco claro en dicha norma. 
     
     Lo que se dice es claro, afirma Google. 
     
     Entonces, aunque generalmente a la autoría de una obra original le sea otorgada protección bajo derechos de autor, la protección concedida a la obra no se extiende a los sistemas o métodos de operación incluidos o incorporados en dicha obra. 
     
     La exclusión legal es explícita y absoluta cuando la norma se refiere a “sin importar la forma” en la cual [el sistema o método de operación] sea descripta, explicada, ilustrada, o incorporada en la obra.
     Afirma Google, que la Corte Suprema de Justicia ha tenido oportunidad de expresar mucho tiempo antes de la sanción de la ley de derechos de autor de EE.UU. en el año 1976, en el caso judicial Baker v. Selden del año 1880, que los sistemas y los métodos de operación (junto con los elementos específicos de la expresión que son “incidentes necesarios” para ellos) no son protegibles bajo derecho de autor.
     
     Entonces, este caso define la importancia de aplicar el artículo 102 inciso b) como está redactado. 
     
     Los encabezados de los métodos de Java o el código fuente declarado de Java, los cuales permiten a los programadores utilizar los comandos abreviados basados en el mismo header o código fuente declarado, a los cuales estos están familiarizados, constituyen un método para operar “los programas pre-escritos de la plataforma Java”.
     
     Si Google no hubiera replicado exactamente los encabezados de los métodos de Java, por ejemplo: 
    
Package.java.lang
public class Math
public static int max (int x,int y)

el código usado por esos comandos abreviados -basados en esos mismos encabezados o código declarado- no hubieran corrido o podido ejecutarse en Android

java.package.Class.method() 

Google se esforzó por replicar sólo los elementos necesarios para permitir a los programadores de aplicaciones en Android de poder usar los mismos “comandos abreviados”, por ello sólo copió los “headers” o código declarado y no así el código fuente implementado que es el implementa o ejecuta los métodos. 

     Si Google no hubiera copiado los “headers” o código declarado de Java en forma exacta (para los 37 paquetes copiados) los “comandos abreviados” no hubieran funcionado, y de esa forma los programadores de aplicaciones en Android no hubieran podido reutilizar el conocimiento adquirido -acerca de cómo invocar las funciones pre-escritas de la librería de software estándar de Java en Android- en forma previa al momento de conocer el lenguaje Java y sus paquetes de API preconstruidos.
     
     El sistema de derechos de autor, no puede bloquear este sistema o método de operación de la misma manera que no puede bloquear el sistema de teclado QWERTY. 
     
     Al presionarse en una tecla sobre un teclado QWERTY el teclado envía un comando que causa que la computadora ejecute una determinada función, como el de escribir la letra Q en una pantalla.  
     
     QUERTY constituye dos cosas: 1) un diseño de teclado y 2) una estructura de comandos para causar en las computadoras todo tipo de producción de letras y símbolos, de la misma manera que los headers o código fuente declarado son la estructura de comandos para utilizar los programas pre-escritos en Java y en Android.  
     
     Que los programadores de desarrollo de aplicaciones hayan invertido tiempo y recursos en el aprendizaje de esos comandos abreviados java.package.Class.method(), confirma el hecho de que los “correspondientes encabezados de métodos o código declarado” del cual derivan los “comandos abreviados” constituye un sistema o método para operar los programas pre-escritos incluidos en la plataforma.
     
     Google no disputa en absoluto que replicó los headers o código fuente declarado que eran más importantes para los dispositivos móviles, y lo hizo precisamente a razón del efecto de bloqueo o lock-in: como los usuarios de computadoras que están familiarizados con el teclado QWERTY, los programadores estaban acostumbrados a utilizar los comandos abreviados de Java basados en el código declarado o headers. 
     
     La decisión de Google fue no utilizar más de aquello que fuera necesario para una plataforma para dispositivos móviles.
     De hecho, este caso es un claro ejemplo de la importancia de la compatibilidad y de los efectos de bloqueo o lock-in. 
     
     Los programadores han invertido tiempo y esfuerzo en aprender el lenguaje de programación Java, incluyendo el formato de comandos abreviado. 
     
     Y ahora, mucho tiempo después de que se ha atraído a los programadores a la comunidad Java, y después de cualquier protección en materia de patentes de invención que ya hubiera vencido, Oracle, el sucesor de Sun Microsystems intenta construir un muro alrededor de los headers o código fuente declarado de Java.  
     
     Por lo expuesto Google afirma que el código fuente declarado o headers no son protegibles por los derechos de autor de EE.UU.
     
     A su vez, Google sostiene que los encabezados de los métodos o código fuente declarado constituye una interface de software, y, por lo tanto, no protegible por el sistema de derechos de autor de EE.UU. 
     
     Cuando IBM creó la computadora personal, desarrolló una interface llamada “Basic Input/Output Systems”. 
     
     Sus competidores como COMPAQ y Phoenix reimplementaron el sistema y crearon sus propias computadoras compatibles con IBM, y ello incrementó el número de opciones disponibles para los consumidores. 
     
     Apple, utilizó aplicaciones de programación de interface existentes en UNIX en el sistema operativo de sus computadoras, permitiendo a los programadores familiarizados en UNIX escribir programas de computación que pudieran ejecutarse o correr en las computadoras de Apple. 
     
     Oracle, construyó su sistema operativo Linux de la misma manera. 
     
     Y en otro orden, para competir en el mundo de los procesadores de texto, Microsoft reimplementó las interfaces de WordPerfect para utilizarlas en Microsoft Word. 
     
     La necesidad y la existencia de las interfaces de software, sin tenerse responsabilidad alguna por infringir derechos, son esenciales, y más hoy en un mundo interconectado.  
     Las leyes locales e internacionales reflejan la importancia de proteger el derecho al uso de las interfaces. 
     
     Por un lado, el Congreso de los EE.UU., cuando se refiere a la posibilidad de realizar ingeniería inversa para propósitos de identificar y analizar aquellos elementos de un programa de computación que son necesarios para lograr la interoperabilidad de un programa creado en forma independiente con otros programas. 
     
    Por otro lado, la Directiva de Software de la Unión Europea 91/250/EEC del 14 de mayo de 1992, dispone excepciones similares para casos de ingeniería inversa para blackboxes o “cajas negras”. 
    
     Estas leyes tienen sentido, porque una vez que se identifica y analiza el código de computación de un programa que es necesario para lograr la interoperabilidad, los programadores poseen el derecho de usarlo, tal cual como lo hizo Google en este caso. 
     
     Así recientemente en el caso Europeo SAS Institute Inc. v. World Programming Ltd (Caso C-406/10, año 2012) se ha dicho que ninguna funcionalidad de un programa de computación ni de un lenguaje de programación y de los formatos de archivos de datos usados en un programa de computación con el objeto de ejecutar sus funciones constituyen una forma de expresión de esos programas, y como tales, no están protegidos por los derechos de autor. 
     
     Lo expuesto revela que la comunidad de desarrolladores desde hace tiempo tenía el entendimiento de que las interfaces son libres de ser utilizadas por cualquiera. 
     Este entendimiento es el que ha permitido la innovación. 
     
     La sentencia de la Corte Federal de Apelaciones, impide la interoperabilidad, y priva a los consumidores de los beneficios de la compatibilidad.
     
     En forma previa a decidir sobre el Writ of Certiorari interpuesto por Google, la Corte Suprema de los EE.UU. solicitó la opinión del Abogado General de los EE.UU. [94]  quién el 26 de mayo del 2015 expresó estar de acuerdo con lo resuelto por el Tribunal de Apelaciones del circuito Federal, y por ello, recomendó a la Corte Suprema la denegación de revisión del Writ of Certiorari presentado por Google. 
     
     Posteriormente, la Corte Suprema de Justicia denegó el Writ of Certiorari, por lo tanto, los argumentos de Google no fueron revisados.
