
Marc James' Silk icon set
-------------------------

Plugin page: [http://artifacts.griffon-framework.org/plugin/silkicons-javafx](http://artifacts.griffon-framework.org/plugin/silkicons-javafx)


Provides a shortcut for adding icons based on Marc James' [Silk icon set][1].

Usage
-----

The following nodes will become available on a View script upon installing this plugin

| silkIcon | icon       | String |             | no         |
| *Node*       | *Node*                        | *Property* | *Type* | *Default*   | *Bindable* |
| ------------ | ----------------------------- | ---------- | ------ | ----------- | ---------- |
| silkIcon     | `javax.scene.image.Image`     | icon       | String |             | no         |
| silkIconView | `javax.scene.image.ImageView` | icon       | String |             | no         |

Valid values for `icon` can be obtained by running **silk-icon-selector** and inspecting the tooltip of the chosen icon.

Scripts
-------

 * **silk-icon-selector** - launches a window that displays all available icons (Hover an icon to see the icon name)

[1]: http://www.famfamfam.com/lab/icons/silk/

