# PlgMyQuill

**PlgMyQuill** integrates the Quill rich text editor into LifeTechOCMS, providing a modern WYSIWYG editor for creating and editing formatted content. 

## Features

- Quill rich text editor integration
- Easy installation through LifeTech OCMS
- Designed for use with LifeTech content forms
- Supports rich text formatting
- Lightweight and developer-friendly plugin structure

## Installation

PlgMyQuill can be installed through the LifeTechOCMS Marketplace or directly from the LifeTech OCMS backend `browse online`:

```text
plugins/
└── PlgMyQuill/
    └── Services/
        └── quill.css
        └── quill.js
```

The exact plugin directory may vary depending on the LifeTech installation version.

After installation, make sure the plugin is enabled through the LifeTech plugin's page.

## Loading MyQuill Editor

Add the Quill editor script to the `<head>` section of your theme, layout, module, or page:

```php

    <script src="<?= ltPluginPath() ?>/PlgMyQuill/Services/quill.js"></script>  
```
