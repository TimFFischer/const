====== Const Plugin for DokuWiki ======

Corrections/Additions:
  * Use of §§ instead of %% for constants: §§value1§§
  * Update of the EvalMath lib. This enables new expressions, like: exp(x), power(x,y), floor(x), ceil(x), number_format(x), if(x,y,z), sum(...)
  * Escape "=" sign in value

Be aware: This is an experimental version!

Old documentation for the Const Plugin is available online at:

  * http://dokuwiki.org/plugin:const

(c) 2013 by lisps

This plugin uses the evalmath class (http://www.phpclasses.org/package/2695-PHP-Safely-evaluate-mathematical-expressions.html) by Miles Kaufmann (BSD License).

See LICENSE for license info.
