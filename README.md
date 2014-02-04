VCL Syntax Highlighting Plugin
==============================

This is a syntax highlighting plugin for Varnish VCL files in Sublime Text 2/3 that isn't completely broken. I was using the only other syntax file out there, [zephirworks/Varnish.tmbundle](https://github.com/zephirworks/Varnish.tmbundle), but it was pretty broken for my VCL files. It doesn't support a lot of things, like long strings (`{"string"}` syntax), `.max_connections` in your backends, etc. It also doesn't provide syntax highlighting for functions, variables, etc.

With this plugin, I have fixed many of those bugs and will actively maintain and extend it, as I frequently work with Varnish.

Embedded Ruby
-------------

This syntax definition also supports Embedded Ruby (ERB) syntax highlighting in your VCL files, as some of my Varnish files are generated using ERB + Puppet.
