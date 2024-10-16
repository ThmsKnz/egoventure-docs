<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# GameConfiguration

**Extends:** [Resource](../Resource)

## Description

The configuration of an MDNA game base don MDNA core

## Property Descriptions

### design\_theme

```gdscript
var design_theme: Theme
```

The theme holding all design configurations

### design\_logo

```gdscript
var design_logo: Texture
```

The game's logo

### design\_cursors

```gdscript
var design_cursors: Array
```

Cursors

### menu\_background

```gdscript
var menu_background: Texture
```

The menu background texture

### menu\_music

```gdscript
var menu_music: AudioStream
```

The music playing when the menu is opened

### menu\_switch\_effect

```gdscript
var menu_switch_effect: AudioStream
```

A sound effect to play when the something is pressed

### menu\_button\_effect\_hover

```gdscript
var menu_button_effect_hover: AudioStream
```

A sound effect played when the mouse is over the menu button

### menu\_button\_effect\_click

```gdscript
var menu_button_effect_click: AudioStream
```

A sound effect played when the a menu button is clicked

### menu\_item\_separation

```gdscript
var menu_item_separation: int = 30
```

The main menu item separation

### menu\_saveslots\_background

```gdscript
var menu_saveslots_background: Texture
```

The background texture for the save slots

### menu\_saveslots\_previous\_image

```gdscript
var menu_saveslots_previous_image: Texture
```

The image for the "Previous page" button

### menu\_saveslots\_next\_image

```gdscript
var menu_saveslots_next_image: Texture
```

The image for the "Next page" button

### menu\_saveslots\_empty\_color

```gdscript
var menu_saveslots_empty_color: Color = "0,0,0,0.55"
```

The color used for empty save slots

### menu\_saveslots\_free\_text

```gdscript
var menu_saveslots_free_text: String = "SAVESLOTS_FREE"
```

The text shown under the free save slot

### menu\_saveslots\_page\_label\_alignment

```gdscript
var menu_saveslots_page_label_alignment: int = 0
```

Orientation of save slot page indicator

### menu\_options\_background

```gdscript
var menu_options_background: Texture
```

The background of the options menu

### menu\_options\_speech\_sample

```gdscript
var menu_options_speech_sample: AudioStream
```

The sample to play when the speech slider is changed

### menu\_options\_effects\_sample

```gdscript
var menu_options_effects_sample: AudioStream
```

The sample to play when the effect slider is changed

### menu\_options\_locale\_button\_modulate

```gdscript
var menu_options_locale_button_modulate: Color = "1,1,1,0.2"
```

The modulate color for selected locale flags

### menu\_options\_locale\_button\_modulate\_selected

```gdscript
var menu_options_locale_button_modulate_selected: Color = "1,1,1,1"
```

The modulate color for selected locale flags

### menu\_options\_hide\_language\_selection

```gdscript
var menu_options_hide_language_selection: bool = false
```

Hide the language selection from the options menu

### menu\_quit\_confirmation

```gdscript
var menu_quit_confirmation: String = "DIALOG_QUIT"
```

The confirmation text for the quit confirmation prompt

### menu\_overwrite\_confirmation

```gdscript
var menu_overwrite_confirmation: String = "DIALOG_OVERWRITE"
```

The confirmation text for the overwrite confirmation prompt

### menu\_restart\_confirmation

```gdscript
var menu_restart_confirmation: String = "DIALOG_RESTART"
```

The confirmation text for the restart confirmation prompt

### menu\_message\_load

```gdscript
var menu_message_load: String = ""
```

Notification message when game has been loaded

### menu\_message\_save

```gdscript
var menu_message_save: String = "MESSAGE_SAVE"
```

Notification message when game has been saved

### menu\_message\_align\_horizontal

```gdscript
var menu_message_align_horizontal: int = 1
```

Horizontal alignment of message

### menu\_message\_align\_vertical

```gdscript
var menu_message_align_vertical: int = 2
```

Vertical alignment of message

### menu\_message\_duration\_seconds

```gdscript
var menu_message_duration_seconds: float = 1
```

Duration of message display in seconds

### inventory\_size

```gdscript
var inventory_size: int = 92
```

The vertical size of the inventory bar

### inventory\_texture\_menu

```gdscript
var inventory_texture_menu: Texture
```

The texture for the menu button (on touch devices)

### inventory\_texture\_notepad

```gdscript
var inventory_texture_notepad: Texture
```

The texture for the notepad button

### inventory\_texture\_reveal

```gdscript
var inventory_texture_reveal: Texture
```

The texture for the hot spots reveal button (on touch devices)

### inventory\_texture\_left\_arrow

```gdscript
var inventory_texture_left_arrow: Texture
```

The texture for the left arrow of the inventory bar

### inventory\_texture\_right\_arrow

```gdscript
var inventory_texture_right_arrow: Texture
```

The texture for the right arrow of the inventory bar

### notepad\_hints\_file

```gdscript
var notepad_hints_file: String
```

The path to the hints csv file

### notepad\_background

```gdscript
var notepad_background: Texture
```

The texture in the notepad screen

### notepad\_goals\_rect

```gdscript
var notepad_goals_rect: Rect2
```

The notepad goals label rect

### notepad\_hints\_rect

```gdscript
var notepad_hints_rect: Rect2
```

The notepad hints label rect

### tools\_map\_image

```gdscript
var tools_map_image: Texture
```

The flashing map image

### tools\_map\_sound

```gdscript
var tools_map_sound: AudioStream
```

The sound to play when flashing the map

### tools\_navigation\_width

```gdscript
var tools_navigation_width: float
```

How wide the left and right navigation areas should be in the
four room scene

### tools\_dialog\_stretch\_ratio

```gdscript
var tools_dialog_stretch_ratio: float = 2
```

The stretch ratio that influences the height of the subtitle panel. The bigger
this value, the smaller the subtitle panel.

### tools\_music\_fader\_seconds

```gdscript
var tools_music_fader_seconds: float = 0.5
```

The number of seconds to fade between the two music channels

### tools\_background\_fader\_seconds

```gdscript
var tools_background_fader_seconds: float = 0.5
```

The number of seconds to fade between the two background channels

### cache\_scene\_path

```gdscript
var cache_scene_path: String = "res://scenes"
```

The path where the scenes are stored

### cache\_scene\_count

```gdscript
var cache_scene_count: int = 2
```

Number of scenes to precache before and after the current scene

### cache\_maximum\_size\_megabyte

```gdscript
var cache_maximum_size_megabyte: int = 50
```

Size of scene cache in MB

### cache\_permanent

```gdscript
var cache_permanent: PoolStringArray
```

A list of scenes (as path to the scene files) that are always cached

### cache\_minimum\_wait\_seconds

```gdscript
var cache_minimum_wait_seconds: int = 4
```

The minimum time to show the loading indicator when precaching

### cache\_minimum\_wait\_skippable

```gdscript
var cache_minimum_wait_skippable: bool = false
```

Whether the minimum wait time can be skipped by left clicking

### debug\_display\_scene\_path

```gdscript
var debug_display_scene_path: bool = false
```

Display scene path name in game (only in debug build)

### debug\_message\_align\_horizontal

```gdscript
var debug_message_align_horizontal: int = 2
```

Horizontal alignment of debug message

### debug\_message\_align\_vertical

```gdscript
var debug_message_align_vertical: int = 2
```

Vertical alignment of debug message