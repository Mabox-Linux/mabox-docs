<div class="gal1">
    <a href="../../img/mabox-autostart.jpg" title="Autostart handling in Mabox Linux"><img src="../../img/mabox-autostart.jpg" alt="" /></a>
</div>


Mabox emplea dos métodos de Reinicio:

- Reinicio visual XDG  *(con editor visual GUI)*
- Un script de texto de reinicio nativo de Openbox - *avanzado*


Usted puede fácilmente configurar ambos métodos desde:

**Menu principal** ++super++ -> **Ajustes ** -> **Reinicio** …

o más rápidamente desde  **Menu de ajustes** con el atajo  ++super+s++.

---
## Reinicio XDG  con editor visual GUI
Puede usar el editor visual de reinicio `yautostart` para seleccionar las (mini)aplicaciones o servicios que usted le gustaria inciar con el sistema automaticamente al partir la sesión.

Por defecto en su instalación de Mabox, usted va a encontrar...

*Existen más ítemes en esta lista, solamente aparecen ahi los más importantes para el primer arranque aquí - aquellos que los usuarios necesiten activar o desactivar en el  cajón izquierdo.*

**Activados**:

*Estos servicios se  inician por defecto, usted puede desactivarlos si es necesario*

- **Sesión de tableros Conky**
- **Monitoreo de actualizaciones en línea** - *miniaplicacion pamac en la bandeja de sistema que le avisará de las actualizaciones necesarias disponibles en cualquier momento*
- **Compositor gráfico Picom** - *un compositor de gráfica X necesario para ver imagenes de calidad en pantalla*
- **Gestor de energía** - *uno del escritorio de  Xfce*

**Desactivados**:

*Algunos programas instalados y preconfigurados en Mabox, disactivados por defecto. Actiívelos si usted los necesita.*

- **Toma apuntes ClipIt** - *gestor de apuntes*
- **[Ícono de Volumen](../../apps/volume-icon/)** - *ícono de volumen en la bandeja de sistema en el panel*
- **[Utilidad de sistema GKrellm](../../apps/gkrellm/)** - poderosa  utilidad para monitorear los recursos (flotantes)
- **GKrellm en una panel** - la utilidad de GkrellM ubicada en un panel lateral (izquierdo) (++super+alt+d++ to show/hide)
- **Esquinas activas** - (cornora)
- **Miniaplicación Blueman** - *Gestor de conexiones de Bluetooth*



---
## Archivo de reinicio nativo de Openbox (Manipule cuidadosamente este archivo!)
Para una configuración muy avanzada existe este fichero script en  `~/.config/openbox/autostart`.

Habitualmente no existe necesidad de editar este archivo avanzado, solamente usuarios con amplios conocimientos de Openbox pueden agregar sus propios comandos  de instrucción o bien otros  scripts  allí. 
