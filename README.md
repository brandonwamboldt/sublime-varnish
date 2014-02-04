sublime-varnish
===============

Syntax highlighting for VCL files in Sublime Text that isn't completely broken. I was using the only other syntax file out there, by [zephirworks](https://github.com/zephirworks/Varnish.tmbundle), but it was breaking on my files. It doesn't support a lot of things, like long strings (`{"string"}` syntax), `.max_connections` in your backends, etc.

I aim to fix most of these mistakes.

Embedded Ruby
-------------

This syntax definition also supports Embedded Ruby (ERB) syntax highlighting in your VCL files, as some of my Varnish files are generated using ERB + Puppet.
