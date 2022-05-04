**mb-reset** es un script asistente que puede ser muy útil ante situaciones desafortunadas de sus sistema.

– usted cometió un error fatal editando la configuración avanzada de archivo global de reinicio de Openbox (rc.xml, reinicio) y su sistema dej de funcionar como antes

– usted ha estado usando el sistema de Mabox por mucho tiempo y desea actualizar a las nuevas actualizaciones de ciertos paquetes de ajustes de archivos que no estan en la rama estable, son paquetes de pruebas (para los for menu/paneles, Conky, tint2 etc.)


mb-reset es un script sencillo a usar desde la terminal  y lo único que hace es copiar los archivos originales por defecto de Mabox en el lugar de su directorio de inicio.

Eejecute el programa script desde la terminal de usuario únicamente (no de  root!). Para ver todas las opciones de este programa escriba en una terminal esto:
```
mb-reset
 mb-reset - reestablece/actualiza los archivos de configuracion de Mabox a los originales por defecto.
    Esto solamente afecta a los archivos personalizados para Mabox por defecto únicamente.
    Cuidado que al usarlo usted va a perder sus propias personalizaciones de Temas, paneles, barras, conkys (si hizo algunas anteriormente).

 Uso de: opciones de mb-reset 

 Options:
   Modo Comparativo:
     -c           - compara archivos usando meld GUI (si esta instalado)
                    Permite ver cambios y decidir cual deberia elegir o no.
                    Funciona con  rc.xml,bashrc y archivos de  autoinicio
                    Uso de : mb-reset -c obrcxml | autostart | bashrc
   Modo de sobreescribir :
     obrcxml      - restaura el archivo global de autinicion de rc.xml  OpenBox 
     obautostart  - restaura el archivo  de autoinicio
     bashrc       - restaura el fichero de configuracion de bash  (~/.bashrc)
     terminator   -restaura el archivo de config del terminal  terminator config
     conky        - restaura los archivos predefinios de recuadros de connky en  ~/.config/conky/
     tint2        - restaura los archivos con los paneles predefinidos  tint2 en ~/.config/tint2/
     jgthemes     - restaura los esquemas de colorees para  menu/paneles laterales en ~/.config/mabox/jgobthemes/
     mainmenu     - restaura los archivos principales del menu (favorites.csv)
     leftpanel    - restablece las aplicaciones originales delpanel  lateral izquierdo
     rightpanel   - restablece las aplicaciones del  panel lateral derecho
     logout       - restablece la ventana de salida de sistema



```
