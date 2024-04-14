# AVA_CONT_2_Jordi-Galí

En aquest exercici he practicat Java Script en la programació d'una pàgina web per realitzar entrenaments. En l'encapçalament he copiat una barra de navegació de la biblioteca Bootstrap que no te totes les funcions completament habilitades (desplegable, buscador, etc.) perquè no era l'objecte d'aquest exercici. 

1.Rutines personalitzades:

En el primer apartat hi ha dos camps per introduir i personalitzar un nou entrenament, amb nom de la ruta i distància. Els camps tenen "place holder" i quan cliques apareix un missatge en vermell que indica presionar "enter" per validar i passar.  En el camp de distància si s'introdueix un valor no numéric apareix un missatge que diu "compte, només s'admeten xifres" i si no s'introdueixen xifres no es pot validar el camp. 

Al final de l'apartat hi ha un botó que afegeix l'entrenament introduit a la taula d'entrenaments que ve a continuació. 


2.Establiment d'objectius:

Al segon apartat, Taula d'entrenaments, hi ha una taula amb el llistat dels diferents entrenaments. Una de les columnes té la característica OBJECTIU. La meva idea era afegir més camps en l'apartat anterior d'introduir un entrenament nou on també es pogues introduir aquest apartat.

Al final d'aquest apartat hi ha un botó amb un text previ que explica que serveix per eliminar una de les files de la taula d'entrenaments previament seleccionada. Quan es selecciona una fila aquesta queda resaltada en color blau amb transparència durant uns segons. 


3.Seguiment del progrés:

A l'apartat final on diu Executa un entrenament hi ha un boto que activa un cronòmetre, el cronòmetre que medeix milèssimes de segon, segons i minuts i un botó per aturar el cronòmetre. Quan cliques de nou el botó d'iniciar l'entrenament el cronòmetre reinicia des de 0. 

Quan es clica el botó per detenir l'entrenament apareix una taula que registra la data i el temps de cada entrenament a continuació. 

En aquest aparatat hi ha un text resaltat en color taronja que et retorna a l'inici de la pàgina on hi ha la taula d'entrenament. La meva intenció era vincular un entrenament seleccionat (previament introduit en la personalització) amb el cronometre i la taula de registre dels temps de l'entrenament. 


4.Informació detallada sobre els exercicis:

Al tercer apartat, Taula d'exercicis hi ha una taula amb informació de diferents tipus d'exercicis (nom, imatge, descripció, objectiu i video. 

Cada cop que es carrega la pàgina apareix automaticament un requadre sota el titol FLEXIONS amb un missatge. Al cap de pocs segons desapareix i apareix un altre que indica clicar ara. Si fas click sobre aquest missatge abans que despareixi s'obre un "alert" que t'avisa que ja pots començar aquest exercici més abaix (cronòmetre).

Nota: no he aconseguit que les imatges siguin transformades a blanc i negre fent servir la funció greyscale amb script.  Sospito que es pot deure a la utilització de recursos de bootstrap. De la mateixa manera no he aconseguit questions menors com que determinats camps de les taules predefinides amb la bibilioteca, apareixi el text en negreta entre altres. 


5.Implementació de controls d'entrenament:

Explicat al punt 3.


6.Integració de components multimedia:

Hi ha dos videos de youtube integrats amb scripts de JS. Els videos es poden pausa, reprendre i ampliar a tota la pantalla. 


7.Gestiò d'errors:

Explicat a l'apartat 1 on hi ha el formulari per entrar les dades. 
També hi ha un enllaç a una pàgina en construcció en la barra de navegació de l'encapçalament. Quan arribes a aquesta pàgina trobes un missatge un botó que et retorna a la pàgina original. 


8.Disseny de la pàgina:

Tota la pàgina està disenyada amb dos colors, fons gris i groc. Les lletres son negres o blanques segons convé per mantenir un contrast suficient. Els camps per omplir, les taules i la informació adicional tenen els fons en blanc. 

L'estructura de la pàgina és senzilla: una sèrie d'apartats alineats en vertical en una sola pàgina. Cada apartat te una linea blanca de separació i un títol en "h2".  Els estils estàn extrets i correctament enllaçats amb Bootstrap i afegeixo algunes modificacions específiques dins <style> del <head> per no haver d'enllaçar un altre arxiu CSS i tenir-ho tot en un sol arxiu .html. 

Les funcionalitats de JavaSript es troben al final del <body> en l'html. 

9.Altres consideracions:

He aconseguit generar i modificar les taules d'entrenament i registre amb el cronòmetre però no he aconseguit poder esborrar correctament les files al seleccionar-les. 

