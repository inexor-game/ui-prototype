ui-prototype
============

Prototypes for menus, hud etc. using the CEF (HTML, CSS, JS).

[Demos are available here](https://inexorgame.github.io/ui-prototype/).

## Components

To have a robust component library we can work upon, we have first to settle which interactive components we need.

Examples:
* [Range Slider](http://refreshless.com/nouislider/)
* Tabs
* Pagination/Lazy Loading
* Code Editor (maybe)
* [Notifications](https://docs.atlassian.com/aui/latest/docs/flag.html)
* [Select2](http://embed.plnkr.co/NXhazc3ZTe9rRCFB0iod/preview)

These are web-level components.

More inspiration for what interactive components we need, can be found on the [Atlassian UI docs](https://docs.atlassian.com/aui/latest/docs/auiselect2.html), they have quite an amount of elements.

We will build some components from scratch, having weblike UI in a Game has to be adapted to the needs of the player. Should be more fastpaced than the web we use it.

There are more to come. We have to find that out by thinking about the existing menus and what elements we want to use in order to control them.

Game-level components are [listed in the wiki](https://github.com/inexorgame/inexor-core/wiki/UI-Components).


### HUDS
* Mouse hidden
* May accept key input
* Doesn't accept mouse input
* Example: Console HUD

### Menus
* Mouse visible
* Accepts key input
* Accepts mouse input
* Example: Main Menu

### List of HUDs

* Console HUD
* Game HUD
* Edit HUD
* Texture Browser
* Model Browser

### List of Menus

#### Main Menu
 * Multiplayer
   * Bot Match
   * Server Browser
 * Options
   * Player Settings
   * Name
   * Playermodel
 * Game Settings
  * Keyboard Bindings
    * In-Game-Bindings (WASD)
    * HUD-Bindings
    * Menu-Bindings
    * Script-Bindings
  * Video Settings
  * HUD Settings
    * X, Y, W, H
    * Game Stats
    * ...User Interface

#### GameHUD

* Game state (icons)
* ammo
* flags
* skulls
* Game stats (text)
* Past/Remaining game time
* Frames per second
* Frags
* Flags
* KPD
* Additional info
* Wallclock


#### EditHUD

* Current Texture
* Floatspeed
* Cubesize
* Worldsize
* Octree Stats
