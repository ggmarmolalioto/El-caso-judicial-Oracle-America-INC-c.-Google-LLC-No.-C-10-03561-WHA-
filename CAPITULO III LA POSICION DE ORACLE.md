 CAPITULO III 

LA POSICIÓN DE ORACLE.           

Temario. Los paquetes -programas de computación- pre-escritos de Java. Licenciamiento de la plataforma Java SE. La especificación de la plataforma Java SE. Google copió en forma idéntica el código fuente declarado de 37 paquetes de Java SE para introducirlo en la plataforma Android.
     
Con fecha 12 de agosto de 2010 Oracle demandó a Google por infracción a sus derechos de autor y patentes de invención . 
     
En efecto, Oracle argumentó que Android (incluyendo la máquina virtual “Dalvik” y el “Android Development Kit”) infringía los derechos de Oracle en relación a su tecnología Java. 

En relación a los derechos de autor, Oracle sostuvo que la plataforma Java contiene una cantidad sustancial de material original (como por ejemplo y sin quedar limitado a código, especificaciones, documentación y otros materiales) protegible conforme al sistema de derecho de autor de los EE.UU. (“Copyright Law Act, 17 U.S.C. 101”). 

Que, sin consentimiento, autorización, aprobación o licencia alguna de parte de Oracle, Google violando la ley copió, preparó, publicó y distribuyó material protegido por las leyes de derechos de autor de EE.UU. propiedad de Oracle, o porciones de ellas u obras derivadas de ella. 

Oracle sostuvo que los usuarios de Android, los cuales incluye a los fabricantes de dispositivos (por sus siglas OEM en inglés “Original Equipment Manufacturer”), deben obtener y utilizar porciones de la plataforma Java u obras derivadas de Java, para fabricar y hacer funcionar los dispositivos Android. 

Oracle expresa que tal uso no se encuentra autorizado por Oracle. 

Por lo tanto, Oracle agrega que Google ha inducido, causado y materialmente contribuido a los actos de infracción por parte de terceros, sea mediante su inducción, asistencia a otros, para usar, copiar y distribuir material protegido propiedad de Oracle, o material derivado de ellos.  

Oracle expresa que Java  fue desarrollada originalmente por Sun Microsystems, la cual fue adquirida por Oracle Corporation en enero del año 2010, y posteriormente renombrada como Oracle America, Inc. 

Java fue diseñada para lograr el objetivo de “write once, run anywhere” en un nuevo entorno informático de redes que incluía internet. 

La idea básica detrás de Java es que un desarrollador de software pudiera escribir aplicaciones de software una vez, luego compilarlo en un formato intermedio conocido como “código de bytes de java”, y distribuirlo en forma de archivos de clases (en inglés “class files”) o archivos .jar (en inglés “files jar”). 

Entonces un usuario que quisiese correr la aplicación podría obtener una copia del código byte de la aplicación a través de varios mecanismos, incluyendo su descarga desde la red internet. 

Entonces el usuario podría correr el código usando la máquina virtual de Java (en inglés “Java virtual machine” o por sus siglas “JVM”) que fue escrita para la arquitectura particular de la computadora del usuario. 

La aplicación podría correr en cualquier computadora que tuviese instalado la máquina virtual de Java. 

La consistencia entre la implementación de la máquina virtual de Java de cada plataforma es lograda porque cada una de ellas está en cumplimiento con la especificación de la máquina virtual de Java , por lo tanto, el “java byte code” correrá o se ejecutará como se espera que lo haga.     


LOS PAQUETES -PROGRAMAS DE COMPUTACIÓN- PRE-ESCRITOS DE JAVA

Durante años cuando los programadores querían escribir programas de computación tenían que escoger una determinada plataforma. 

Entonces, cada una de las grandes compañías de tecnología, como Apple y Microsoft, habían desarrollado sus propias versiones de lenguajes de programación. 

Con lo cual, cuando se escribía un programa para las computadoras con Microsoft Windows, ese programa no podía correr o ejecutarse en las Apple MacIntosh. 

Por ende, si alguien quería que un programa de computación pudiera ejecutarse y funcionar en Microsoft Windows y en Apple MacIntosh, debía escribir el mismo programa dos veces. 

Con la plataforma Java, todo esto cambió. 

Publicada en 1996, y con una de sus salientes características la “máquina virtual de Java” (JVM), se permitía escribir programas que pudieran ejecutarse o correr en diferentes computadoras con distintos sistemas operativos, sin que existiese la necesidad de reescribir los programas. 

Lo único que se requería era tener instalado el programa de la máquina virtual de Java donde se iba a ejecutar ese programa desarrollado en cuestión. 

Por lo tanto, una vez escrito un programa podría correr o ejecutarse ese programa en cualquier computadora sin importar su sistema operativo instalado (MS, Linux, Solaris, etc.), lo único que se exigía era tener instalado el programa de la máquina virtual de Java. 

Esto es el “write once, run anywhere”, “escrito una vez, corre en cualquier lado” -queriéndose hacer referencia a cualquier sistema (hardware más sistema operativo).

Los desarrolladores de Sun Microsystems crearon una cantidad importante de programas de Java con la finalidad de llevarse a cabo funciones usualmente requeridas para desarrollar o programar “otros programas de computación”, y organizó estos programas pre-escritos en “paquetes” (en inglés “packages”). 

El conjunto de estos paquetes o programas pre-escritos es lo que se conoce como la librería de software estándar de Java o librería de clases de Java. 

Estos paquetes están acomodados u ordenados en una estructura compleja. 

A su vez, esta estructura consiste en numerosos módulos de programas probados, testeados y confiables (en inglés “trie-and true”), que comprenden una gran cantidad de funciones.

Estos “paquetes de Java” fueron de gran utilidad para que otros programadores pudieran escribir o crear sus propios programas de aplicaciones para diferente tipo de dispositivos. 

Entonces, estos programadores ante la necesidad de una determinada funcionalidad en su desarrollo no tenían que “reinventar la rueda”, sino por el contrario, podían echar mano a cualquiera de los paquetes de Java que incluyera la funcionalidad necesitada por ellos. 

También, los programadores podían escribir dicho programa conteniendo la funcionalidad deseada por ellos “desde cero”, es decir, no era obligatorio usar esos paquetes de Java en la construcción de sus nuevos programas. 

En el juicio, tanto por el Juez de Distrito como por las partes, a estos paquetes de software se los denominó “API”. 

Oracle menciona que el término API, que significa “aplicación de programación de interface” es confuso, porque es una suerte de “camaleón” (en inglés “verbal chamaleon”), ya que puede describir un protocolo de comunicación común o trivial como sería pasar información entre programas de computación, o puede describir programas sofisticados, como los escritos por Sun Microsystems y que son objeto del presente juicio. 

En el presente litigio, la Corte de Distrito y las partes han confusamente aplicado el mismo significado para describir “al conjunto de paquetes de Java” y al “código fuente de un sólo paquete de Java”.

Entonces, a modo ilustrativo en un paquete de Java, los desarrolladores de Sun Microsystems escribieron un programa llamado “URLConnection” -que es un programa de computación, no un protocolo de comunicación trivial o simple entre programas) para establecer la conexión a internet (por ejemplo, con un banco o una tienda on-line). 

Más allá de que parezca simple, es extremadamente complejo. 

Los desarrolladores de Sun Microsystems eran expertos en protocoles de redes y algoritmos criptográficos. 

El código fuente declarado (o declaración o| método de encabezado) para URLConnection es:

public   URLConnection    openConnection()
trhows java.io.IOException

Entonces, digamos que un tercero desea desarrollar una aplicación o programa para que se pueda conectar con BankofAmerica.com

Así, ese tercero (programador) puede (i) reinventar la rueda, escribiendo su propio algoritmo, o (ii) simplemente usar el código disponible pre-escrito por Sun Microsystems/Oracle, y para ello debe “declarar” en su propio programa, tipeando el código fuente de más abajo el cual va a invocar o llamar al código pre-escrito por Sun Microsystems:

new URL(“http://bankofamerica.com”).openConnection()

A medida que los distintos programadores conocen y hacen uso de estas funcionalidades en forma frecuente, la utilización de los paquetes de Java se convierte en un hábito de la programación en el lenguaje Java, y los programadores no necesitan saber o mirar dentro de él, ya que lo que les interesa, es la funcionalidad que cumple y que ellos necesitan para incorporar a sus propios programas.

Cada paquete de Java consiste en dos tipos relacionados de código fuente, código declarado y código implementado. 

Entonces, cada componente en un paquete de Java comienza con una o más líneas, incluyéndose entre otras cosas, de una “descripción de la función”, como puede ser utilizando el ejemplo anterior “public URLConnection openConnection() throws java.io IOException” . 
     
También, este código refleja el “lugar” del componente dentro de la estructura del paquete de Java. 

A su vez, un código similar, es el que los programadores (nuevamente los terceros que construyen otros programas, por ejemplo aplicaciones, utilizando los paquetes de Java) deben declarar con el objeto de invocar el programa pre-escrito de Java, y en el caso, sería las línea de código expresado en el ejemplo anterior “URL(String spec).openConnection()”. 

A este tipo de líneas de código se las conoce como declaraciones, encabezados, firmas o nombres dependiendo de algunos factores que no son relevantes para el caso en particular. 

Entonces, a estas líneas de código se las llama “declaraciones” o “código fuente declarado”. 

El segundo tipo de código fuente, el código implementado, le indica a la computadora “como” llevar a cabo o ejecutar una función declarada. 

En el ejemplo mencionado, el código implementado sería las líneas de código indicando la apertura de la conexión de internet.

Estos programas pre-escritos están interconectados a través de una estructura, secuencia y organización. 

A su vez, los programas están organizados dentro de “paquetes”, y cada paquete se organiza en un conjunto de clases, y cada clase es organizada a su vez en un conjunto de métodos, los cuales cada uno de ellos cumple una función específica, como por ejemplo la de abrir una conexión a internet. 

Estos paquetes de software -nuevamente se menciona- son los denominados como API en el juicio. 

En la figura de más abajo se muestra la estructura de los paquetes y las clases, sin mencionarse en ella la complejidad de los 30.000 métodos.

[IMAGEN- ver en issue]

Cada una de las líneas representa las opciones disponibles para los programadores de paquetes y clases. 

Como se dijo anteriormente, los terceros programadores en la construcción de sus propios programas usando el lenguaje de programación Java, no tienen ninguna obligación de usar estos paquetes de Java “pre-escritos” por Sun Microsystems (a excepción de 170 líneas de código incluidas en tres paquetes de Java en: Java.lang, Java.io y Java.util). 

En definitiva, quien desee usarlos para construir sus propios programas puede hacerlo, y quién no, puede desarrollar desde cero la misma funcionalidad -u otras no previstas en los paquetes de la librería de software Java- que sean necesarias según cada programador. 

A su vez, Sun Microsystems especificó como trabaja el código de los paquetes en un documento que se denominó “Especificación de las API de Java”, que contiene más de 40.000 páginas y que detalla el código declarado de Java y su estructura organizacional. 

La especificación de la API además describe la estructura y organización de cada uno de los paquetes de Java, -además de toda la estructura de todos los paquetes de Java-. 

La especificación de Java, se “espeja exactamente” en el código declarado de los paquetes, incluyendo su estructura y organización.

La edición original de la plataforma Java Edición Estándar (Java SE) de 1996 tenía 8 paquetes de programas pre-escritos. 

En 2005, cuando Google comenzó a copiar el código declarado, la versión de Java SE 5.0 tenía 166 paquetes, y así fue evolucionado, y por ejemplo en febrero de 2011 alcanzó a los 209 paquetes. 

La creación de estos paquetes constituyó un proceso creativo e interactivo. 

Parte de la creatividad se relaciona con establecer “que incluir” en cada uno de los paquetes y “como organizar” el código declarado de manera tal que el uso por parte de los programadores en la construcción de sus propios programas sea “intuitivo”.  

El código declarado puede ser muy extenso en su expresión creativa, por ejemplo: 

public abstract void verify (PublicKey key, String sigProvider) 
throwsCertificateException,No-SuchAlgo-rithmException, InvalidKeyException,
NoSuchProviderException, SignatureException

El proceso de creación comienza con la identificación de áreas de necesidad de nuevas o diferentes funciones por parte de los desarrolladores de Oracle en la comunidad del lenguaje de programación Java. 

Las sugerencias, incluso, provienen del Comité Ejecutivo de Java (en inglés “Java Executive Comittee”) compuesto por Oracle, y empresas tales como IBM y Google . 

Sun Microsystems y Oracle invirtieron varios millones de dólares en el trabajo de creación de los paquetes de Java. 

Y ello incluyó la enseñanza en la comunidad de desarrolladores en cómo utilizar cada uno de esos paquetes de Java, de manera tal que cuando un programador de Java veía “URL.openConnection(),” sabía instantáneamente que eso significa “crear una conexión de internet”, tan fácil y simple como eso. 

LICENCIAMIENTO DE LA PLATAFORMA JAVA SE

Oracle menciona que los varios componentes que conforman la plataforma Java SE (el lenguaje de programación Java, el Java “runtime enviroment” (que incluye la máquina virtual de Java, la librería estándar de Java y las API, y el “Java development kit” que incorpora una colección de programas de herramientas, incluyendo al compilador de Java) se licencia bajo diferentes “tipo de licencias”, pero todas ellas poseen un objetivo común: “proteger la compatibilidad de Java”. 

Entonces, más allá de los derechos de autor (conforme al régimen legal de los EE.UU.) sobre la plataforma Java SE propiedad de Oracle, Oracle promovió la utilización de los paquetes de Java por terceros, y para acomodar las necesidades de todos los interesados utilizó tres tipos de licencias, que son las siguientes:  

a)	Licencia (libre y código abierto) Pública General, versión 2 (en inglés “General Public License, version 2” o sólo “GPL v2”) : Bajo este esquema de licencia de software libre y código abierto (FOSS) los licenciatarios podían ver, reproducir, modificar (y crear obras derivadas) y distribuir el código fuente de los paquetes de Java (en inglés “Java packages”), tanto del “código declarado” como del “código implementado”. 

b)	Licencia de especificación : mediante esta licencia a diferencia de la licencia GPLv2, los licenciatarios sólo podían acceder a la especificación de la plataforma Java SE (que recita el código fuente declarado). Es decir, esta licencia no permitía a los licenciatarios utilizar el “código fuente completo de Java”. Por lo tanto, los licenciatarios utilizando sólo el código fuente declarado y la estructura de organización brindada por Oracle, debían desarrollar o construir su propia implementación independiente (es decir este tipo de código fuente) del conjunto de las API de Java o paquetes de Java. Entonces, esta licencia de especificación suponía un esquema de: código fuente declarado de Sun Microsystems/Oracle + código fuente implementado del licenciatario de la especificación de Java (con el TCK aprobado lógicamente) = Código Binario Ejecutable del Licenciatario de la Especificación (que constituiría la implementación independiente de Java por parte del tercero respetando el principio de “write once, run anywhere” instituído por Sun Microsystems/Oracle).

c)	Licencia comercial: mediante esta licencia los licenciatarios tenían acceso completo al código fuente (declarado e implementado) de Java con la finalidad de poder usarlo y adaptarlo para incorporarlo a sus propios productos comerciales y pudiendo mantener en secreto su código desarrollado. A cambio de ello, los licenciatarios debían pagar una regalía a Oracle. 

En definitiva, ambas opciones a) y c) daban acceso por completo al código fuente (declarado e implementado) propiedad de Sun Microsystems/Oracle. 

En el caso a) la opción bajo la GPLv2 implicaba que en caso de distribución de Java de “cualquier modificación” calificable como obra derivada bajo el sistema de derechos de autor de EE.UU. al producirse la distribución debía ser hecha disponible bajo los mismos términos y condiciones de la licencia GPLv2. (lo mismo aplicaba si la distribución de Java se producía sin modificaciones, ya que el disparador de la licencia conforme sus términos es la distribución) 

La opción c) también daba acceso por completo al código fuente, pudiéndose modificar o adaptar Java, sin tener que publicar o hacer disponibles dichas modificaciones a terceros, con la única condición de tenerse que pagar una regalía a Sun Microsystems/Oracle.   

Ahora bien, tanto la licencia comercial como la licencia de especificación debían pasar el denominado TCK o test de compatibilidad de Java. (no así el licenciamiento bajo la GPLv2)


LA ESPECIFICACIÓN DE LA PLATAFORMA JAVA SE

Sun Microsystems publicó la especificación de Java (protegida por derechos de autor) y ofreció licenciarla bajo determinadas condiciones.

Así para el caso de la especificación de la plataforma Java 2 Edición Estándar, Sun Microsystems permitía a los desarrolladores crear implementaciones independientes (en inglés“clean room”) de la especificación de la plataforma Java de Sun Microsystems con la condición de que se cumpliera con los requerimientos exigidos por su licencia de especificación. 

Estos requerimientos, conforme Oracle eran los siguientes: 

(i)	que se incluya una implementación completa de la versión actual de la especificación sin realizar “subsetting” o “supersetting ”, 

(ii)	que se implemente todas las interfaces y funcionalidades del paquete requerido por la plataforma Java 2, Edición Estándar definidas por Sun Microsystems sin realizar “subsetting” o “supersetting”, 

(iii)	 No agregar ningún paquetes, clases o interfaces a los paquetes java.* o javax.* o a los subpaquetes de estas, 

(iv)	 aprobar todos las pruebas o test relativos a la más reciente versión publicada de la especificación de la plataforma Java 2, Edición Estándar, las que eran disponibles por Sun Microsystems (en inglés “Technology Compatibility Test” o “TCK”) seis (6) meses antes de cualquier versión beta publicada de la implementación independiente o de la actualización establecida en ella,  

(v)	que la implementación independiente no contenga código fuente u materiales binarios de propiedad de Sun Microsystems, y  

(vi)	que la implementación independiente no incluya código fuente o materiales binarios de Sun Microsystems sin una licencia apropiada y separada otorgada por Sun Microsystems.  
Oracle sostuvo que Google no cumplía con las condiciones enumeradas anteriormente conforme a la licencia de especificación de la plataforma Java 2, Edición Estándar. 

También se sostiene por Oracle que los desarrolladores estaban en total conocimiento que la licencia de especificación de Sun Microsystems requería las pruebas de compatibilidad usando el TCK de Sun Microsystems, el cual menciona Oracle estaban disponibles y sin requerirse pago alguno para universidades, colegios, organizaciones sin fines de lucro, y personas físicas en http://java.sun.com/scholarship  


GOOGLE COPIÓ EN FORMA IDÉNTICA EL CÓDIGO FUENTE DECLARADO DE 37 PAQUETES DE JAVA SE PARA INTRODUCIRLO EN LA PLATAFORMA ANDROID. GOOGLE QUEBRÓ EL PRINCIPIO WORA

Google pudo haber escrito sus propios paquetes para su plataforma Android en el lenguaje de programación Java, y no hay nada objetable en este punto. 

Por el contrario, lo cuestionable, y lo que Google hizo fue copiar 37 paquetes de Java en forma idéntica. 

Google copió los 37 paquetes de Java que creía que los programadores de Java querrían encontrar en Android, así “invocables” por los programadores para ser utilizados en la construcción de sus propios programas en la plataforma Android -no ya en la plataforma Java que son incompatibles- bajo los “mismos nombres” que se usaban en la plataforma Java. 

Esta copia idéntica (reconocida por Google en el pleito) del código fuente declarado de los 37 paquetes de Java implicó la copia idéntica de la estructura de cada uno de los 37 paquetes, y luego Google “parafraseo” el código fuente implementado, es decir, con la especificación de las API de Java que espeja el código fuente declarado Google sólo siguió la “guía” de la especificación y completo los “espacios en blancos”. 

En definitiva, Google hizo lo que otras empresas que tomaron la licencia de especificación hicieron (ya que estas empresas podían hacerlo porque poseían justamente una licencia de especificación otorgada por Oracle), sin cumplir claramente Google con los requisitos de compatibilidad del TCK (diferencia de los que poseían una licencia de especificación). 

Al ser incompatible Android con Java, Oracle menciona que Android es la única implementación de la especificación de Java incompatible con Java, es decir, Google quebró la especificación de Sun Microsystems, el lema “write once, run anywhere”, siendo el lema de Android “write once, run only in Android”. 

Google hizo la parte más fácil, la menos compleja al parafrasear el código fuente implementado. 

La figura de más abajo muestra el paquete de Java denominado java.io. Este paquete maneja inputs y outputs. 

[ver IMAGEN en issue]

Sobre la izquierda se encuentran las numerosas clases, por ejemplo, InputStreamReader (que traduce un flujo de datos en texto legible para humanos). Las clases a su vez, pueden contener subclases, y a su vez, las subclases pueden contener sub-subclases, y así sucesivamente. 

Google copió el código declarado del paquete java.io incluyendo todas sus clases. La figura no nuestra todos los métodos, que son un total de 569, distribuidos dentro de aproximadamente 50 clases. A su vez, la clase InputStreamReader tiene 5 métodos. Otras clases dentro de java.io poseen entre 3 y 39 métodos. Google, copió también en forma idéntica el código declarado de todos los métodos.

Por su parte, la figura de más abajo muestra lo copiado por Google a nivel método respecto del paquete de Java denominado java.security

[ver IMAGEN en isse]

Las líneas que parecen imperceptibles son los 362 métodos. 

Google copió en forma idéntica los 362 métodos. 

El código declarado que define el método o clase incluye más información que sólo el nombre y su función. 

De hecho, la mayoría incluye “parámetros”, que define su operación (por ejemplo: “5” directs java.io.StringReader.skip para saltear los próximos 5 caracteres). 

La estructura de los paquetes de Java no es simplemente lineal o puramente estructural. 

Un esquema real sería uno tridimensional con interconexiones complejas. 

Entonces, habría que mirar la figura de arriba y pensar en los grupos marcados en color como si fuese el plano de un piso en un edificio de 50 pisos, con una red de toboganes y escaleras que conectan cada uno de los pisos, e incluso que conectan con otros edificios, representando a los demás paquetes de Java. 

Estas conexiones son “interfaces” (que no se deben confundirse con la terminología de “interfaces” asociadas al juicio como API) con grupo de clases compartiendo características similares. 

Así la figura java.io muestra la interface sobre la derecha en itálica conectando una clase con otra clase, dentro del mismo paquete y en otros paquetes de Java. 

Entonces lo copiado por Google habría que multiplicarlo por los 37 paquetes de Java, con unas 677 clases, y unos 6508 métodos aproximadamente, totalizando al menos unas 7000 líneas de código declarado .  

La copia de Google causó la fragmentación que Sun Microsystems y Oracle querían evitar. 

A su vez, a pesar de que Google copió en forma idéntica el código fuente declarado de los 37 paquetes de las API de Java con la finalidad de atraer a los programadores de Java a su plataforma Android, Google diseñó Android para ser incompatible con la plataforma Java, es decir que las aplicaciones escritas para Android no funcionan en Java, y las escritas para la plataforma Java no funcionan en Android. 

A su vez, ningún programa escrito para la plataforma Java antes de la existencia de Android, funciona en la plataforma Android. 


[CAPITULO III contiene las notas 23 A 32]
