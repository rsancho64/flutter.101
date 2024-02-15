[MoureDev](https://www.youtube.com/watch?v=-pWSQYpkkjk)

flutter permite crear una única app que se puede ejecutar en
diferentes sistemas ¿por qué existe el desarrollo nativo?

- que es flutter cómo funciona
- pros y cons
- instalar todo el entorno de desarrollo
- app 101-

dos grandes formas de desarrollar apps móviles

- herramientas nativas del sistema ...
  [swift](https://developer.apple.com/swift/) (apple);
  hot link (android)
- ... y librerías ()

que nos proporciona el propio equipo de
google y android estos dos sistemas independientes se desarrollan de la mano
del propio OS y tienen un soporte directo de apple y de google
siempre que se evoluciona el OS son en estos dos sistemas en
los que primero es implantar sus cambios y en los que también se añaden las
mejoras mejoras de seguridad formas de interactuar con el OS y
el hardware así como distintos componentes visuales básicamente esto es
a lo que me refiero con plataformas de desarrollo nativo puro

por otro lado tenemos los sistemas multiplataforma o híbridos que permiten crear una única app
que corre en diferentes sistemas entre los que se encuentra a flutter o quizás otras tecnologías que te pueden sonar como **reactive**, **johnny**, **xamarin** otras mucho más obsoletas como
puede ser fonda o **córdoba** básicamente los sistemas
multiplataforma funcionan de dos grandes maneras los sistemas multiplataforma
híbridos utilizan web views básicamente nosotros lo que estamos utilizando es
una web toda la capa visual se está renderizando sobre un explorador web
aunque eso sigue dando una apariencia propia de apps móviles estos
sistemas cada vez están más en desuso ya que su rendimiento y su nivel de
integración con el propio OS es muy bajo por otro lado
tenemos multiplataforma pueden ser el propio flutter que se engloban dentro de
los sistemas multiplataformas nativos porque su nivel de integración es mucho
mayor un motor de renderizado gráfico que sí que interactúa de forma nativa
con el propio OS vale

si tenemos sistemas multiplataforma y nativos ¿por que utilizar los sistemas nativos puros de android por un lado y de apel por otro- precisamente porque tenemos pros y contras en cada uno de los ecosistemas y muchas veces no los conocemos por eso es esencial saber cómo funciona cada
sistema para así tomar la decisión más correcta para tu desarrollo

en primer lugar te diré que igual que flutter ya existen otro tipo de tecnologías muy
parecidas y que flutter no es la primera ni será la última de este tipo

personalmente pienso que flutter es una grandísima alternativa y que funciona mucho mejor que sus
predecesores pero nada nos asegura que le pase lo mismo que a estas tecnologías que aparecían y eso es algo que tienes que tener presente de todas formas que esto no te agobie como
desarrolladores y desarrolladoras continuamente nos estamos renovando y no quiere decir que si elegimos una tecnología tenemos que continuar con ella el resto de nuestra vida

android y google desarrollan primeramente para sus sistemas nativos puros y una vez éstos
evolucionan les toca a las multiplataforma -por ejemplo a flutter- ir incorporando cada uno de esos cambios con lo cual siempre iremos un pasito por detrás

también se aparece algún error en los sistemas nativos puros primero se tendrán que corregir en ellos y después también se tendrá que adaptar flutter

otra cosa importante es que las apps multiplataforma pesan mucho más que las apps nativas puras
-estamos hablando de una capa por encima de los sistemas nativos y todo esto deriva en
escalabilidad, rendimiento y eficiencia.

puede derivar en apps menos escalables
en el momento que hablamos de apps muy grandes que tienen que crecer y que tienen que utilizar las
últimas características incluidas, estos sistemas multiplataforma pueden quedarse algo limitados

aún así esto tampoco tiene que preocuparte ya que inflaron por ejemplo podremos
programar una parte común que se ejecute en diferentes sistemas operativos y realizar desarrollos por separado por ejemplo para android para ios utilizando esos y para este tipo de desarrollos el
lenguaje nativo y las librerías propias del sistema esto quiere decir que utilizando una única base de app podremos especializar lapor separado

en rendimiento y eficiencia, resumiendo mucho, flutter no utiliza de forma tan óptima el sistema y no optimiza tanto los recursos del sistema provocando en algunos casos que por ejemplo utilice más memoria batería o que según como sea en nuestra interfaz de usuario pueda ir algo más lenta con
la app nativa pura

aún así estos son casos muy concretos en el caso de flutter como te estoy diciendo su desempeño es muy

¿cuando debe utilizar sistemas nativos y cuando multiplataforma ?

cierto que una gran mayoría de las apps de más alto nivel y de grandes empresas son nativas puras pero existen otras empresas de primer nivel que están decidiendo utilizar flutter

a tener en cuenta: la escalabilidad de nuestra app; características que va a poseer si de verdad nos vamos a tener que integrar muy a bajo nivel con componentes del propio OS y en muchos casos también el presupuesto que tenemos para desarrollarla.

habitualmente es más barato desarrollar apps con flutter que con sistemas nativos pero -se han dado casos de apps- se puede comenzar desarrollo multiplataforma y en el momento de crecer todo se complica.y hay paso a sistemas nativos diferenciados.

(el dinero ahorrado al principio supone después desembolso más grande y en el momento de tomar estas decisiones nunca nos olvidemos de
app en

Es cierto que flutter es tecnología google ,, relación estrecha con android, pero apple funciona totalmente por separado y que las decisiones que tomen nos pueden afectar negativamente

El mejor desarrollador multiplataforma conoce los sistemas nativos puros. android o los operativos de apple funcionan de forma diferente y la UX es distinta. ver flujos dentro de una a nivel de interfaz gráfica y de usabilidad son dos sistemas diferentes algo que tendrás que tener en cuenta cuando desarrollo es confiar

A día de hoy flutter (by Google) es la mejor alternativa multiplataforma que tenemos.

podemos crear una única app que se ejecuta en diferentes sistemas no sólo en ios sí en android sino que también podremos crear apps para web o incluso para sistemas de escritorio, ***todo esto, y en cierto modo, con un único desarrollo*** claro es una tecnología de código abierto y tendrás toda la información relevante y sus novedades en **[flutter.dev](https://flutter.dev/)**

realizar estos primeros pasos y la configuración del propio sistema una vez conocido que es flutter deberemos hablar de que el LP utilizaremos ya que

flutter en sí es el sdk. Pero tendremos que interactuar con él de alguna forma. Para ello utilizaremos el LP **[dart](https://dart.dev/)** -se presenta en 2017- y surge como *una alternativa a javascript* de la mano de google.

de código abierto aunque es un lenguaje creado por google su uso no está muy extendido pero sí que es cierto que gracias a flutter se está impulsando algo muy importante de
dart tb funciona bajo una MV y esto ++productividad (rapida ejecución + *hot reload* -recargar la vista sin reiniciar todo el contexto- e gráficos.)

se integra perfectamente con todas las plataformas y nuestro código creado con dart de la mano de flutter acabará compilando en nativo para diferentes sistemas tanto mobile como web como de escritorio en dar punto de tendrás toda la información relevante e incluso podrás probar cómo funciona el lenguaje con el propio playground que tenemos integrado en la web en el que estarás viendo por ejemplo cómo se hace un holamundo también dispondrás de muchos recursos para aprender cómo funciona toda la  doc y tutoriales

muy bien tenemos flutter por un lado y su LP dar cómo funcionan entre ellos para acabar por ejemplo dibujando una interfaz gráfica aquí es donde entra **[skia](https://skia.org)**, motor de renderizado 2d también de google y también de código abierto. (renderizado de objetos no nativos)

### 101 @ linux

- [ ] web de flutter / started instant* ... howto flutter // instalación prácticamente igual en cualquier sistema .. try `flutter doctor -v` to check all ok

la
documentación oficial de flutter nos recomienda tres opciones 
- la primera es android estudio o inteligente android y estudio el ido oficial para crear apps nativas puras android e intel y jesse live creado por jetbrains en el que se basa el propio 'no de estudio pero en caso de seleccionar uno de estos dos yo te recomendaría siempre android estudio ya que está pensado directamente para crear apps android y posee ciertas características que nos van a ayudar a desarrollar de una forma mucho más óptima y productiva
- otra opción también es el conocidísimo editor visual studio code y ya por último utilizando 
- imax (un entorno de programación mediante línea de comandos 

@@@@

En mi caso recomiendo android estudio ya que cuando creamos una app con flutter en realidad estamos dando soporte a una app tanto android como ios y android estudios da precisamente pensado para desarrollar apps y que confiar él también nos va a permitir ejecutar apps ios siempre que estemos dentro del OS mac
o es para descargar android de estudio
lo podrás hacer desde la web oficial de
desarrolladores android developer punto
android puntocom si quieres ver todo
este proceso con más detenimiento te de
juntos por aquí aunque básicamente es
descargarlo descomprimirlo e instalar
una vez iniciamos android studio nos
iremos a la sección de plugins y en esta
buscaremos flutter y lo instalaremos una
vez lo instalemos tendremos que
reiniciar el ine también revisa que
junto con el plugin de flutters instale el
plugin de dar una vez hecho esto en
proyectos ya tendremos un nuevo botón
que nos dirán inflar yo proyecto lo
pulsaremos para crear un nuevo proyecto
aquí podremos realizar diferentes
configuraciones sobre todo para indicar
dónde están todas las utilidades que
necesitamos para desarrollar una
app en flutter por ejemplo el
propio directorio donde teníamos el sdk
lo habitual es que no tengas que tocar
nada en esta parte ya que estará todo
correctamente configurado una vez
seleccionamos flutter podemos pulsar en
siguiente y aquí empezar a introducir
datos de nuestra nueva app por
ejemplo cómo le vamos a llamar le
llamaremos hello flight la nomenclatura
tendrá que ser en minúsculas y separadas
mediante guiones bajos le podremos dar
una descripción seleccionar cuáles son
los lenguajes nativos de estos sistemas
en el caso de que tengamos que hacer
desarrollo especializados para cada
sistema dentro del propio flora y
también las plataformas que vamos a
soportar en nuestro caso por defecto
android y ios hecho esto pulsaremos en
finalizar se creará el proyecto en el
directorio que hemos indicado
harán ejecutarse todos los procesos de
configuración en android studio lo
primero que veremos es un ritmo con
enlaces a diferente documentación
importante como puede ser la
especificación de la propia apio o
incluso tutoriales veamos la estructura
principal del proyecto tendremos dos
directorios uno android y otro ios
básicamente este es el proyecto nativo
android y este es el proyecto nativo ios
proyectos que podríamos utilizar tanto
en android studio como scout siempre que
hablemos de los proyectos nativos de
cada sistema también tendremos un
directorio de tests y la parte principal
que deberemos conocer que es el
directorio live básicamente el lugar
donde tenemos el código común de nuestra
app flar el código que se va a
ejecutar tanto en android como año es
por supuesto tenemos mucho más ficheros
pero que se corresponderían con un
tutorial más avanzado en este vídeo lo
que queremos conocer cómo funciona flutter
y cómo crear esta primera app si
abrimos el fichero main punto art lo que
veremos es lo siguiente un fichero con
un montón de anotaciones donde se nos
explica paso por paso que se está
haciendo en cada caso te recomendaría
que leyeras toda esta documentación pero
para que lo veamos mucho más simple lo
que yo voy a hacer es borrarla y así
quedarnos únicamente con el código
escrito andar aunque antes de revisar un
poco por encima código o lo que haremos
será ejecutar nuestra vamos a ejecutar
nuestro hola mundo en flutter en la parte
superior tendremos que tener
seleccionado el fichero dark principal
de la app que se llamará main dar
y dentro del desplegable podremos ver
los diferentes simuladores en los que
podremos ejecutar la app vemos que en mi
caso es el simulador de ios ya que yo
estoy emma cohen sí y un pixel 3 y un
pixel 4 que yo tenía configurados ya en
android estudio si quieres configurar tu
emulador androide tendrás que ir a esta
opción al a vd manager aquí podrás crear
diferentes simuladores que corran bajo
and muy bien seleccionemos en primer
lugar nuestro pixel 3 para ejecutar
nuestra app flutter en android una
vez hecho esto se va a abrir el emulador
y una vez inicializa dow ya podremos
volver a la interfaz de android studio y
pulsar el botón play para ejecutar
nuestra app dentro del emulador que
hemos seleccionado en este caso dentro
de android y aquí la tenemos la
app que se crea por defecto en
flash es una app que ya vemos que
tiene un texto que tiene una barra de
navegación un contador y un botón más
que si nosotros pulsamos veremos que el
contador se va incrementando hagamos lo
mismo pero mayores volvamos al listado
de simuladores y en este caso seleccione
hay un simulacro por ejemplo en este
caso un iphone 13 una vez seleccionado
el simulador pulsaremos el botón play y
ocurrirá lo mismo que en el emulador
android y aquí lo tenemos como vemos el
propio flutter se ha encargado de realizar
algunas modificaciones ya que no es lo
mismo como se ve la barra de navegación
en android quien ios pero ciertamente la
funcionalidad y lo que estamos viendo en
cada una de las apps es lo mismo todo
con un único código entendamos muy por
encima el código escrito en de arte de
nuestra app toda la parte de interfaz
gráfica con flar editar se va a
estructurar en los llamados widgets
básicamente diferentes componentes
gráficos algo así como pequeñas vistas
cada una con funcionalidades diferente
vemos que tenemos un widget principal
que va a representar la ejecución
inicial de nuestra app como tenemos un
tema para configurarlo a nivel de color
que está utilizando un color azul que es
el que veíamos en la app como tenemos un
título que dice planes demo y como en la
parte home le estamos pasando un nuevo
widget en realidad una interfaz gráfica
se construye gracias a diferentes
widgets a este widget el hemos llamado
my home page un widget al que le pasamos
un título que dice flutter demo homepage
que por supuesto se corresponde con el
título que tenemos aquí en la parte
superior si nosotros
este título y dijésemos hola flutter aquí
veremos otra de las características más
importantes de flutter que gracias a
correr sobre una máquina virtual puede
hacer uso del llamado terry loud
simplemente voy a guardar el fichero y
voy a volver a los simuladores el último
simulador que ejecutamos fue el de ios
simplemente con guardar el fichero ya se
ha actualizado sin necesidad de volver
inicializar el emulador si esto mismo lo
hacemos con el de android veremos que
los dos se ha actualizado otra forma de
forzar el repintado es utilizando este
botón que tenemos aquí que ya dice flutter
reload sigamos viendo nuestra interfaz
gráfica como nuestra home page está
almacenando un título y un estado que le
llama my home page state básicamente
tenemos un componente que engloba todo
el contenido de la pantalla que tiene
una pac que es la barra superior con un
título que le hemos pasado es widget
punto title el título que estábamos
definiendo aquí arriba y que aparte de
la barra tiene un body un cuerpo de la
pantalla centrado y con un hijo a modo
de columna que va a establecer
componentes uno encima de otro estos
componentes serán un texto que por
ejemplo lo vamos a cambiar que
modificado su texto por as pulsado el
botón todas estas veces el mecanismo de
jauri lo aquí lo tiene actualizado por
último en esta columna tenemos otro
texto que se corresponde con el contador
y que va a utilizar la variable counter
para representar su valor el paradigma
utilizado por darte es declarativo
estamos haciendo uso de programación
funcional y de estados una forma de
programar muy actual y que las
tecnologías más modernas ya usan por
ejemplo en los sistemas android tenemos
programación funcional y declarativa
gracias al LP
court link y a hierbas campos para crear
interfaces gráficas y por la parte de
entornos appel tenemos a swift como
LP y a sitio hay
como paradigma declarativo para crear
las interfaces ya por último vemos un
botón un botón que va a llamar a una
función cuando hagamos clic en él y esta
función lo único que va a hacer es
incrementar el contador en uno esta
variable contador de tipo entero es lo
que estamos pintando en el campo texto
por eso en el momento que nosotros
empezamos a pulsar en el botón se llama
esa función se incrementa el contador y
vamos mostrando el nuevo valor de la
variable content ya ves lo fácil que
está estructurado el código y como creo
que se entiende bastante bien que hace
cada parte como te decía todos los
componentes visuales de flutters se llaman
widgets podemos construir con widgets
simples otros más complejos pero sí que
es cierto que tenemos que podemos
utilizar como base y los puedes
encontrar todos en la sección de widgets
en la documentación oficial de flutter
como ves tenemos un montón pero por
ejemplo nosotros vamos a crear un botón
si buscamos la palabra button verás como
tenemos diferentes y algunos que les
precede la palabra cupertino en este
caso los componentes con la palabra
cupertino delante están asociados a
componentes que solemos estar
acostumbrados a vernos en ios y si
buscamos la palabra material serán
componentes que estamos más
acostumbrados a ver en entornos andrew
por ejemplo nosotros vamos a utilizar el
botón que estamos acostumbrados a ver en
android que se llama el flutter elevated
button como añadiremos un botón en
nuestro código con dart simplemente por
ejemplo dentro de la columna a
continuación del texto del contador voy
a añadir un nuevo widget que como vimos
se llama el debate paz aquí tendremos
que definir los parámetros qué va a
pasar cuando lo pulsamos nosotros vamos
a hacer exactamente lo mismo que cuando
pulsamos este botón que como vimos era
una llamada a esta operación a
incrementar counter una operación
definida como void que está cambiando su
estado básicamente es una especie de
función pero que nosotros en dar y flave
tendremos que definir de esta forma así
que voy a llamar en el momento que se
pulsa a esa operación y como todo widget
contendrá un hijo en este un hijo que se
puede corresponder con el texto que
vamos a representar dentro del botón
como es el componente texto ya lo vimos
se llama texto ese hijo lo vamos a
definir de tipo texto y constante y el
texto que va a mostrar el botón ser a
incrementar contador si hacemos esto y
nos vamos al simulador vemos que ya
tenemos un botón un botón que tiene la
apariencia del botón de android pero
ejecutándose en ios con esto es lo que
te quería explicar que directamente no
es que estemos utilizando el botón de
sistema sino que mediante skip a ese
motor de renderizado 2d se está pintando
en el canvas un botón desde hacer un
botón con una apariencia concreta y que
por supuesto si lo pulsamos vemos cómo
realiza la misma acción que el botón
flotante y el contador se incrementa y
por supuesto esto mismo también lo
podremos ver en el emulador de anne y
estuviéramos soporte a más sistemas como
linux como web también podríamos ver
esto estos flutters y esta es su potencia
la capacidad de crear una única
app que se ejecute en diferentes
entornos pero sin olvidar los pros y los
contras de los que te ha hablado al
principio del vídeo pero sin duda la
mejor opción multiplataforma que tenemos
actualmente viene por comentarios que te
ha parecido y recuerda que todos los
enlaces de interés a la documentación
estarán en la descripción si te ha
gustado este tutorial ya sabes al botón
de suscribir y activa la campanita es la
forma más fácil que tienes de apoyarme y
no te olvides de seguirme en redes
sociales tienes todos los enlaces de
interés en moure punto de recuerda que
estoy en twitter en instagram y que hago
directos de lunes a viernes hablando
sobre programación y tecnología en
tweets puedes unirte también de forma
gratuita a nuestro servidor de discos
donde ya somos más de 4000 y si aún
quieres apoyar más a la comunidad puedes
utilizar el mecanismo de miembros del
canal en youtube y de suscriptores en
twitch de verdad muchísimas gracias por
todo el apoyo mostrado semana a semana
espero que os haya gustado este vídeo
diferente y publicado en un día muy
especial del año pero que al margen de
que en el canal sobre todo hablemos de
apps nativas también tengáis en
cuenta que existen otras opciones y que
debemos de ser conscientes cuando
utilizar unas u otras aunque yo siga
apostando por el desarrollo nativo puro
como una opción de futuro a continuación
te dejo con otros vídeos que te pueden
interesar muchísimas gracias por llegar
hasta el final del vídeo y a los
miembros de la comunidad roswell
rodríguez y control por regalarme esta
camiseta de batman espero que este
tutorial os haya despejado dudas nos
vemos muy pronto hasta otra hacker men
