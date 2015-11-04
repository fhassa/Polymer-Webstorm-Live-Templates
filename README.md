# Polymer Live Templates for WebStorm
===========================

Live templates to be used in WebStorm with Polymer (Polymer-Project)


##Introduction

This repository contains LiveTemplates for [Polymer](http://polymer-project.org/) to be used with [JetBrains](http://www.jetbrains.com/) products such as [WebStorm](http://www.jetbrains.com/webstorm/).

Live Templates are a set of abbreviations that expand in to 'code snippets' for common tasks such as creating variables and functions. 
These abbreviations significantly speed up development and reduce coding errors.

##Installation

WebStorm does not have any particular installation (or import) procedure for LiveTemplates.
Instead just drop `Polymer.xml` file from this repository into WebStorm's folder where it stores LiveTemplates.

Live templates are stored in the following location:

```
Windows: <your home directory>\.<product name><version number>\config\templates
Linux: ~\.<product name><version number>\config\templates
MacOS: ~/Library/Preferences/<product name><version number>/templates
```


##How to use the Live Templates
Type  (eg. pe) then hit `tab` to auto-complete,
OR, start typing the prefix for an element and hit `ctrl+space` to fuzzy search for a completion

## Elements

Type the name of [any `iron-*` or `paper-*` element](https://elements.polymer-project.org), then hit `tab` to auto complete.

![Using snippets](https://cloud.githubusercontent.com/assets/1066253/8323071/77f4173c-19f4-11e5-94d2-a22e3b3e526e.gif)

## Polymer

### [pe] polymer element

```html
<dom-module id="$NAME$">
    <style>
        
    </style>
    
    <template>
        
    </template>

    <script>
        Polymer({
            is: "$NAME$",
            
            properties: {
              $END$       
            }
        })
    </script>
</dom-module>
```
