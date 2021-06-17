## Al extintor

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada



# 1 Datos 



**Titulo** : Al extintor

**Web:**   cebollesfrites.github.io

**Autor:**  Alicia Díez Ratón

**Resumen** : Al extintor es un pequeño juego con una orientación infantil. Consiste en guiar a Alex, una pequeña llama, que se ha separado de su madre por las diferentes salas de una mazmorra. La forma de avanzar es encontrando rastros de objetos quemados, ceniza, etc.

**Estilo/género:**  Juego

**Logotipo** : ![imagen]

(insertar imágenes a resolucion de 100px alto)

**Resolución:** 800x600px no se puede reescalar 

**Probado en:**   Google Chrome 

**Tamaño proyecto:** 63MB

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 16/06/2021

**Medios** (donde se tiene presencia relacionada):

- Github:Cebollesfrites


![logo](https://github.com/Cebollesfrites/cebollesfrites.github.io/blob/master/logo.png)

# 2. Memoria del proyecto 

### 2.1 Storyboard: 
 El juego comienza con una pequeña animación de un pasillo que acaba dando a una puerta. Esta se abre y aparece el menú de inicio (la animación inicial se puede saltar con un botón de skip) en el que aparece el personaje y un tablón con dos papeles. Uno de ellos es el menú con las opciones play y galería y el otro explica en que consiste el juego. Además arriba a la derecha hay otro pequeño tablón que al pulsarlo lleva a los créditos. 
 El botón galería lleva a otra pantalla en la que se pueden ver las imágenes usadas para la animación del principio. Al darle al botón play se pasa a otra habitación de la mazmorra en la que hay tres puertas y numerosos objetos. Cinco de esos objetos son interactivos, tres de ellos siendo opciones incorrectas y dos de ellos siendo correctas (las respuestas correctas son aquellas que están chamuscadas). Tienes dos vidas; al perderlas sale un cartel anunciando que has perdido y al pulsar una de las opciones correctas aparece otro cartel felicitándote y dando paso a lo que sería el siguiente nivel (esto es un nivel piloto por lo que no hay otro nivel).




### 2.2. Esquema de navegación 



(imagen con las distintas pantallas de navegación, usa draw.io o cualquier programa de dibujo)







# 3. Metodología

Metodología de desarrollo de productos multimedia basado en una metodología de UX (User Experience)



### Etapa 1: Ideación de proyecto

**Investigación de campo** (propuestas inspiradoras para el proyecto)

- La estética está inspirada en la animación inicial de los episodios de Detective Conan.
- El diseño del personaje está basado en el del personaje Fuego del juego Fuego y Agua.



**Motivación de la propuesta** 

El juego tiene un público objetivo infantil, a mí cuando era pequeña Fuego y Agua me marcó mucho y pensé en hacer algo similar dentro de los límites del programa. A partir de eso tomé la decisión de que se formasen niveles, siendo cada uno de ellos una habitación diferente con diversos objetos, algunos de los cuales sirviesen para avanzar la historia.



**Publico / audiencia**

- Orientado a un público entre los 7 y los 13, pero jugable para todos los públicos.





### Etapa 2: Desarrollo / actividades realizadas

(qué soluciones has planteado y cómo se han resuelto: juego, galería de fotos, grabación de video, etc.)

- **Juego**  El crear el juego me supuso un reto bastante grande pues nunca había tenido que hacer un proyecto siquiera similar. Al ser mi primera introducción a la programación no pude arriesgarme a hacer algo extremadamente complicado (tampoco es que el programa diese muchas opciones), pero aún así creo que quedó algo jugable que al final era la intención. 
El juego persé consiste en una habitación con tres puertas y numerosos objetos. Cinco de ellos son interactivos, tres incorrectos y dos correctos. Todos ellos son botones; los incorrectos restan un punto de la variable vidas (Se puede ver en un cuadro de texto en la parte superior y desde el principio se parte teniendo dos) y los correctos suman. Al pulsar cualquiera de ellos la imagen se amplía y bajo esta aparece un letrero diciendo si has perdido un punto o ganado, para salir de ello hay un  hotspot ante el cual pulses lo que pulses, lo que no sean los objetos hechos grandes, vuelves al estado original (me parecía la forma más intuitiva de hacer que el juego continuase). El hotspot esta ligado los carteles que anuncian si has ganado y perdido, si lo pulsas teniendo 3 o 2 vidas te aparece el cartel diciendo que has ganado. Sin embargo, cuando lo pulsas teniendo 0 te aparece el de que has perdido. 
- **Video** A la hora de poner el vídeo decidí usar unas llamas que se mostrasen en el momento en que aparece el título, pues se veía muy vacío. El vídeo se reproducía desde el principio mientras que para salir del título hay que pulsar el botón start en la esquina inferior derecha de la pantalla. Al final acabé quitándolo pues no terminaba de encajar con la estética del juego. Todas las imágenes del juego están dibujadas por mi con una estética y gama cromática concreta por lo que añadir algo semirealista quedaba fuera de lugar. 
- **Instrucciones y ayuda al usuario** Al ser un juego con un público objetivo infantil, la idea era hacerlo lo más intuitivo posible. En la pantalla del menú aparecía un cartel contando la historia de Alex (El hecho de que se ha separado  su madre y tienes que encontrar pistas para saber por donde se ha ido).
- **Menús y elementos de navegación (botones)** Al igual que con las instrucciones los botones también son lo más intuitivos posible. Los de el menú tienen escrito literalmente a donde llevan, al igual que los de créditos, start y skip. El resto de botones son simplemente flechas, que las he intentado colocar de forma que se entienda a donde llevan (si vuelven al menú o pasan los elementos de la galería). 
- **Elementos gráficos** Como dije mi inspiración fueron la introducción de la serie de animación Detective Conan y el juego Fuego y Agua. La forma en que los mezclé junto con mi propio estilo artístico fue usar el diseño de personajes e integrarlo en una estética ligeramente más oscura, como de mazmorra. Para el diseño de personaje barajé varias opciones, incluso que no fuese una llama, pero al final acabé escogiendo el diseño actual porque era el más adorable.
- **Musica** Para la música de fondo tenía claro que quería que fuese algo alegre que no se hiciese particularmente pesado, y que a poder ser encajase con la animación inicial. Para ello barajé varias opciones, pues si tenía letra se acabaría haciendo cansina pero sino no llegaba a ser lo suficientemente pegadiza. La forma de resolver este problema fue que la canción fuese una cover de Totakeke (un personaje del Animal crossing que se ha convertido en un banco de voz) de  Buttercup de Jack Stauber.


### Etapa 3: Problemas identificados

Actualmente el principal problema que no he conseguido resolver es que al ser los elementos interactivos botones en sí mismos, puedes pulsarlos varias veces accidentalmente, estropeando el sistema de vidas.
Además de eso nunca fui capaz de poner un modulador de volumen pues cada vez que lo ponía el programa crasheaba, teniendo que usar un backup para poder seguir trabajando. Ni el profesor ni yo supimos a que se debía esto por lo que no fue posible arreglarlo.

# 4. Conclusiones 
 Este trabajo siento que ha sido una una experiencia bastante enriquecedora, me habría gustado poder trabajarlo en un año normal pues he sentido que la programación Covid-19 no me ha dejado aprovechar la asignatura al máximo. Aún así creo que para no haber tenido ninguna experiencia programando y el haber aprendido brevemente como hacerlo tan cerca de la entrega final, el resultado es bastante decente. 
 Además de esto me ha agradado mucho el sentimiento de comunidad que se ha generado en la clase para resolvernos mutuamente los problemas, para ser un proyecto bastante estresante ha aliviado mucho.
 Con todo esto creo que el resultado ha sido bastante interesante y creo que intentaré añadir el resto de los niveles como proyecto personal, pues he trabajado mucho en todas las ilustraciones y programación como para dejarlo como un trabajo inacabado.







# 5 Referencias 

**Artículos y blogs ** 

- Crofts, S., Fox, M., Retsema, A. and Williams, B. (2005) *Podcasting: A new technology in search of viable business models*First Monday, 10(9). https://doi.org/10.5210/fm.v10i9.1273. Recuperado el 8 de abril de 2020 de: https://journals.uic.edu/ojs/index.php/fm/article/view/1273/1193

**Recursos y materiales audiovisuales:**

* Musica: Buttercup Tatakeke cover, Jack Stauber.  
* Imágenes: Iluatraciones por Alicia Díez Ratón
* Tipografía: Alicia Díez Ratón y Palatino. 

**Herramientas utilizadas**

- Hippani Animator 5.1
- Photoshop Cs.6
- Paint Tool SAI
- Procreate
- PicsArt




https://creativecommons.org/licenses/?lang=es

Mayo 2020
