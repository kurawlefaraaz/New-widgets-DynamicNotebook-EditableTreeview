# tkinter-pp
A collection of tkinter made widgets

# Widgets included

## Calendar widget
Displays a calendar so that the user can enter a date.

## CloseableNotebook widget
A subclass of the `ttk.Notebook` widget, with a closing button, so the tab destroys itself.

## ScrolledCanvas widget 
A `tk.Canvas` instance, which has scrollbars built-in to scroll the Canvas in any direction.

## EntryWithPlaceholder
A `tk.Entry` which provides a greyed-out placeholder if nothing is written inside, and unfocused

## KeybindingEntry
A `tk.Entry` which reacts to key presses, so that you can record keybindings in a tkinter-friendly way.

## EntrySelectFolder
A `tk.Entry` which provides a button to select a folder using `tkinter.filedialog.askdirectory`.

The path writes itself inside the entry.

## DialogueEntry
A dialogue box with a `tk.Entry` inside.


# Assets included

Some xbm bitmaps are available as well, in a string form. Use `tk.BitmapImage(data=..., mask_data=...)` to create the bitmaps.

The assets are available in the "assets" submodule. Use `import tkinterpp.assets` to import.