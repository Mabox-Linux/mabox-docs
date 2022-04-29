
**Espanso** is a cross-platform text expander written in Rust.

Espanso detects when you type a keyword and replaces it while you're typing.

_See it in action..._
![Espanso - text expander](../img/espanso.gif)

This is useful in many ways:

- Save a lot of typing, expanding common sentences.

- Create system-wide code snippets.

- Execute custom scripts

**Key Features**

- Works with almost any program

- Works with Images

- Date expansion support

- Custom scripts support

- Shell commands support

- App-specific configurations

- Support [Forms](https://espanso.org/docs/forms/)

- Expandable with packages

- Built-in package manager for [espanso hub](https://hub.espanso.org/)

- File based configuration



## How to run espanso in Mabox?

Espanso is preinstalled in Mabox, all you need to do is register user systemd service for it. This is needed to automatically start espanso at system startup.

```
espanso start
```



## Mabox espanso helper
Espanso is great piece of software, but currently it lacks GUI - for example to remind you all defined triggers.

This is why Mabox provide a simple GUI for that - use ++super+alt+e++ to invoke simple espanso helper :)

<div class="gal1">
    <a href="../../img/espanso_helper.jpg" title="Mabox Espanso helper"><img src="../../img/espanso_helper.jpg" alt="" /></a>
</div>



You will see menu showing all defined triggers and sentences/snippets (type to search also works here). Menu gives you also easy acces to espanso config directory, editing default config file and link to [Espanso documentation](https://espanso.org/docs/).

!!! info "Next Espanso version is currently in development"
    Development of next - significantly improved version of Espanso is already at an advanced stage.
    Therefore, soon the Mabox helper will be able to retire :)
