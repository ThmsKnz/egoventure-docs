<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# main\_menu.gd

**Extends:** [CanvasLayer](../CanvasLayer)

## Description

The MDNA main menu

## Constants Descriptions

### MINIMUM\_SAMPLE\_TIME

```gdscript
const MINIMUM_SAMPLE_TIME: float = 2
```

Minimum number of seconds a speech or background sample should
be played

## Property Descriptions

### resumeable

```gdscript
var resumeable: bool = true
```

Wether the main menu can be hidden

### saveable

```gdscript
var saveable: bool = true
```

Wether the a game can be saved

### disabled

```gdscript
var disabled: bool = false
```

Wether the menu can be displayed at all

## Method Descriptions

### configure

```gdscript
func configure(configuration: GameConfiguration)
```

Configure the menu

** Parameters **

- configuration: The game configuration resource

### toggle

```gdscript
func toggle()
```

Toggle the display of the menu and play the menu music

### main\_menu\_is\_displayed

```gdscript
func main_menu_is_displayed()
```

Returns true if the main menu is shown and no pop-ups are shown

## Signals

- signal new_game(): Emitted when the user wants to start a new game
- signal quit_game(): Emitted when the user wants to quit the game
