
**Espanso** es una plataforma extensiva de texto escrita en Rust.

Espanso detecta cuando uno escribe una palabra clave y la reemplza mientras esta escribiendo.

_Véalo en acción..._
![Espanso - text expander](../img/espanso.gif)

Esto es útil en muchas formas:

- Ahorra un montón de escritura, expandiendo frases comúnes.

- Crea un sistema amplio de codigos rápidos (code snippets).

- Ejecuta scripts personalizados

**Caracteríticas claves**

- Funciona en la mayoría de los programas

- Funciona con imágenes

- Soporta expansiónes de fechas

- Soporta scripts personalizados

- Soporta comandos de terminales

- Ajustes de aplicaciones  específicas

- Soporta formularios [Forms](https://espanso.org/docs/forms/)

- Paquetes de extensiones 

- Gestor incoroporado para  [espanso hub](https://hub.espanso.org/)

- Ajustes basados en archivos



##¿Cómo ejecutar espanso en Mabox?

Espanso esta  preinstalado en Mabox, todo lo que necesita hacer es registrarse como ususario en los servicios de systemd  para usarlo. Esto es requerido para emplear espanso automaticamente en el incicio de sesión.

```
espanso start
```



## Asistente espanso de Mabox
Espanso  es sensacional como software, pero carece de aspecto visual GUI - por ejemplo para recordarnos todos registros ya definidos antes.

Por esta razón Mabox ofrece una versión visual GUI para esto - use ++super+alt+e++ para llamar el asistente visual de espanso :)

<div class="gal1">
    <a href="../../img/espanso_helper.jpg" title="Mabox Espanso helper"><img src="../../img/espanso_helper.jpg" alt="" /></a>
</div>



Verá un menu mostrándole todos los registros previos ya definidos en frases, claves  (anote para ubicarlos eso tambien funciona aquí). El menu le ofrece fácil acceso al directorio de configuración de espanso, editando el archivo de config por defecto y con un vínculo a una guía de  [Espanso documentation](https://espanso.org/docs/).

!!! info "Viene una version de Espanso en desarrollo"
    Desarrollo de la nueva versión - significativamente mejorada y ya esta en una etapa más avanzada.
    Por lo tanto , pronto, sera el nuevo asistente de Mabox helper y será posible que me jubile  :)
