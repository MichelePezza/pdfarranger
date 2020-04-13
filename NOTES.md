* <https://developer.gnome.org/gnome-devel-demos/stable/menubar.py.html.en>
* <https://stackoverflow.com/questions/22578346/python-gtk3-toolbar-accelerator-doesnt-work>
* <https://lazka.github.io/pgi-docs/Gtk-3.0/classes/Application.html*Gtk.Application.add_accelerator>
* <https://lazka.github.io/pgi-docs/Gtk-3.0/classes/Widget.html*Gtk.Widget.set_tooltip_text>
* <https://gitlab.gnome.org/GNOME/pygobject/blob/master/gi/overrides/Gio.py*L137>
* <warning: https://gitlab.gnome.org/GNOME/pygobject/issues/29>
* <https://lazka.github.io/pgi-docs/Gio-2.0/classes/ActionMap.html*Gio.ActionMap.add_action_entries>
* <https://lazka.github.io/pgi-docs/index.html*Gtk-3.0/classes/Application.html*Gtk.Application.set_accels_for_action>

```python
print(Gio.Action.print_detailed_name(self.impl.window.lookup_action("rotate").get_name(), GLib.Variant.new_int32(90)))
Gtk.accelerator_name(Gdk.KEY_Delete, 0)=='Delete'
```

## GMenu migration

* <https://gitlab.gnome.org/GNOME/gtk/blob/master/demos/gtk-demo/shortcuts-builder.ui>
* <https://lazka.github.io/pgi-docs/Gtk-3.0/classes/ShortcutsWindow.html>
* <https://gitlab.gnome.org/GNOME/Initiatives/-/wikis/App-Menu-Retirement>
* <https://developer.gnome.org/hig/stable>
* <https://gitlab.gnome.org/GNOME/meld/-/blob/master/meld/meldwindow.py>
* <https://gitlab.gnome.org/GNOME/meld/-/blob/master/meld/resources/ui/appwindow.ui>
* <https://developer.gnome.org/gtk3/stable/GtkPopover.html>
* <https://gitlab.gnome.org/GNOME/gtk/issues/903>

## 1.5.0 TODO

* Update screenshot
* Wait for german translation
* Add release in appstream file
* Try to do the windows release with Arch Linux, Wine and Docker
* Check .msi size after release
* Remove the Quit menu
