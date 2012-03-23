# Detroit Commons

[Website](http://detroit.github.com) /
[Development](http://github.com/commons)


## Description

Detroit Commons is a meta-package that incorporates [Detroit](http://detroit.github.com)
and the majority of it's official plugins.


## Instruction

The purpose of this meta-package is to make it a simple one line entry in
a project's requrements list in order to get Detroit and all the plugins 
that a project might use.

Strictly speaking,it is of course more *economical* to only require detroit and
the specific plugins your project needs. But in general practice it won't
ofter matter, since if other projects use other plugins then there's
a good chance that all the plugins are already installed and unutilized
plugins will not be installed in any case. In other words, use `detroit-commons`
and forget about it.


## Exclusions

A few offical detroit plugins that one can find in the GitHub detroit organization
are not included in this meta-package, namely `detroit-grancher` and `detroit-rubyforge`.
The former is excluded because it's common usage has been usurped by the `detroit-github`
package. And the later has be excluded because RubyForge is no longer the common
Ruby project hosting service. Any of these plugins can be added to requirements
list of a project separately if they are needed.


## Copyrights

Copyright (c) 2012 Rubyworks

Distributable under the terms of the **GPLv3+** license.

See LICENSE.txt for details.

