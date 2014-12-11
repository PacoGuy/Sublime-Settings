Sublime-Settings
================

A modified preference file for sublime.

Modified code changes the User Preferences to:
- Monokai theme
- Phases the caret in a pulsing manner
- Makes folders in Side Bar bold
- Keeps code folding arrows visible
- Sets font size to 20
- Highlights the line the caret is presently in
- Sets top and bottom line padding for better readability
- Word Wrap is on by default <!-- EXPERIMENTAL Let me know if this causes issues -->
- See below for additonal settings, need to add info on each setting

The `Preferences.sublime-settings` file code can replace with no modification into the (Sublime: Preferences: Settings - User) file

Note- File created on Linux Sublime Text 3, needs to be tested on other environments

Note- Method to have preferences file automatically modified would be nice

Contents of Preferences.sublime-settings:
================

```css
{
	"bold_folder_labels": true,
	"caret_style": "phase",
	"color_scheme": "Packages/Color Scheme - Default/Monokai.tmTheme",
	"fade_fold_buttons": false,
	"font_size": 20,
	"highlight_line": true,
	"line_padding_bottom": 1,
	"line_padding_top": 1,
	"tab_size": 2,
	"save_on_focus_lost": true,
	"trim_trailing_white_spaces_on_save": true,
	"ensure_newline_at_eof_on_save": true,
	"word_wrap": true, //EXPERIMENTAL Let me know if this causes issues
	"ignored_packages":
	[
		"Vintage"
	]	
}

```
