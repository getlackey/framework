# Lackey options parser

Keeps all lackey modules in a single dependency

This module is the [Lackey framework](https://www.npmjs.com/package/lackey-framework) that is used to build the [Lackey CMS](http://lackey.io) amongst other projects.

## Documentation

- [Inline Edit](https://www.npmjs.com/package/lackey-inline-edit)
- [Make Title](https://www.npmjs.com/package/lackey-make-title)
- [Options Parser](https://www.npmjs.com/package/lackey-options-parser)
- [JSON XLSX Converter](https://www.npmjs.com/package/lackey-json-xlsx)
- [Dustjs Helpers](https://www.npmjs.com/package/lackey-dustjs-helpers)

## Usage

    var lackey = require('lackey-framework'),
        inlineEdit = lackey('inline-edit'), // or require('lackey-framework/inline-edit')
        makeTitle = lackey('make-title'), // or require('lackey-framework/make-title')
        optionsParser = lackey('options-parser'), // or require('lackey-framework/options-parser')
        JsonXlsxConverter = lackey('json-xlsx'), // or require('lackey-framework/json-xlsx')
        dustjsHelpers = lackey('dustjs-helpers'); // or require('lackey-framework/dustjs-helpers')
