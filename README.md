# Helpful Code/Dev snippets

Just a handleful of code/commands that I like to copy and paste every so often.

## Table of Contents

  1. [MAMP](#mamp)
  1. [Javascript](#javascript)
  1. [VIM](#vim)
  1. [PHP](#php)
  1. [Github](#github)
  1. [Gravity Forms](#gravity-forms)
  1. [MySQL](#mysql)
  1. [Codesniffer](#codesniffer)
  1. [Terminal](#terminal)
  1. [Sass](#sass)
  1. [Cron](#cron)
  1. [Codeception](#codeception)
  1. [Sublime Text](#sublime-text)

## Javascript

```
(function($) {
    $(document).ready(function() {

    });
})(jQuery);
```

```
(function ($){
  console.log("scripts.js loaded");
})(jQuery);
```

View list of all JavaScript variables in Google Chrome Console
```
for(var b in window) {
  if(window.hasOwnProperty(b)) console.log(b);
}
```

## PHP

## MAMP

PHP INI
```
/Applications/MAMP/bin/php/php7.1.12/conf/php.ini
```
Logs
```
/Applications/MAMP/logs
```

## VIM

Copy all the lines to clipboard
```
gg"*yG
```
