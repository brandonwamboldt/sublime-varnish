VCL Syntax Highlighting Plugin
==============================

This is a syntax highlighting plugin for Varnish VCL files in Sublime Text 2/3 that isn't completely broken, and supports the majority of Varnish VCL features.

It's been written from scratch and is extremely fast. Some of the other VCL tmLanguage files floating around there have causing my Sublime Text CPU usage to spike because of their complex regex. This plugin has no such issue.

If I've missed something, please open an issue so I can fix it (or send me a Pull Request). I work with Varnish daily, so I'll be actively maintaining this plugin.

![screenshot](https://github.com/brandonwamboldt/sublime-varnish/blob/master/screenshot.png?raw=true "Screenshot using SpaceGray theme")

Snippets
--------

There are a bunch of snippets in the `Snippets/` folder, please look there for more information.

- `acl` - Creates an ACL
- `backend` - Creates a backend
  - `probe` - Add a `.probe` definition to your backend
- `deliver` - Replace with `return (deliver);`
- `director` - Creates a director
- `if` - Creates an if statement
- `log` - Replace with `std.log("");`
- `lookup` - Replace with `return (lookup);`
- `pass` - Replace with `return (pass);`
- `restart` - Replace with `return (restart);`
- `sub` - Creates a subroutine
