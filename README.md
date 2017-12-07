# ckeditor-pastebase64
This plugin is designed to make the pasting of image data (not html) consistent across browsers. So that Chrome/Firefox/IE/Edge will all paste an <img> with a base64 data URI when pasting image data from the clipboard. This image data typically comes from screenshots or copying directly from image editing software.

# What is CKEditor?
CKEditor is a WYSIWYG text editor. See [the official site](http://ckeditor.com) for more details.

# Requirements
[JavaScript File API](https://developer.mozilla.org/en-US/docs/Web/API/File).
 Tested and working in Chrome/Firefox/IE/Edge. Does not work in Safari.

# Plugin installation and setup
1. Copy the plugin files to the plugins directory (/ckeditor/plugins/pastebase64/)
2. Ensure to reference the plugin.js file from your html file after ckeditor.
3. Enable the plugin by using the extraPlugins configuration setting. Example:  
CKEDITOR.config.extraPlugins = "pastebase64";
