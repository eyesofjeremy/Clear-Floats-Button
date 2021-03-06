# Clear Floats Button

Adds clear float button to TinyMCE Editor. Originally by [Miguel Ibero](https://wordpress.org/plugins/tinymce-clear-buttons/).

## Description

This plugin adds 1 button to [TinyMCE](http://tinymce.moxiecode.com/) to clear floating elements. It also adds divs to valid tags so they won't be deleted if empty.

## Installation

1. Download.
2. Unzip.
3. Upload to the plugins directory (wp-content/plugins).
4. Activate the plugin.

## Changelog

### 1.0.8
- Compatibility with future version of WP

### 1.0.7
- Fixed miss interpretation of TinyMCE api regarding custom_elements. This prevented the plugin from working in IE [Issue #3](https://github.com/Graffino/Clear-Floats-Button/issues/3)

### 1.0.6
- Compatibility with future version of WP

### 1.0.5
- Fixed stripping of IDs on DIVs - Extended valid elements fix for cases in which extended elements are not defined [Issue #1](https://github.com/Graffino/Clear-Floats-Button/issues/1)

### 1.0.4
- Fixes not loading CSS when user is not logged-in [Issue #2](https://github.com/Graffino/Clear-Floats-Button/issues/1)

### 1.0.3
- Updated assets for WP Plugin Directory (2)

### 1.0.2
- Updated assets for WP Plugin Directory

### 1.0.1
- Fixed stripping of IDs on DIVs - Extended valid elements fix [Issue #1](https://github.com/Graffino/Clear-Floats-Button/issues/1)

### 1.0.0

- Created new version from [stale plugin](https://wordpress.org/plugins/tinymce-clear-buttons/)
- Revamped graphic assets
- Removed clear:left and clear:right buttons
- Changed plugin so we don't have inline styles.

## Frequently Asked Questions

1. Why do you need to clear the floats?
Well, sometimes you want to add two floating images but don't want them to overlap. Or you want to add an image floated to the left and text on the right, and then add a new block. You can add a clear in
the middle to achieve the desired effect.
