@bender-tags: mentions, feature, 4.10.0, 1972
@bender-ui: collapsed
@bender-ckeditor-plugins: wysiwygarea, toolbar, basicstyles, mentions

1. Focus the editor.
1. Type first marker character listed below i.e. `@`.
1. Wait until dropdown appear.
1. Repeat for each listed marker character. 

Marker characters:
* `@` synchronous array feed.
* `$` asynchronous URL string feed.
* `#` asynchronous callback feed.

## Expected

Dropdown appears after delay - above 3 seconds.

## Unexpected

Dropdown appears almost immediately.
