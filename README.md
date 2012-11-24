Mono-A-Mono
===========

> from one monkey to another


Mono-a-mono is a build-pack that aims to make developing with Open Source .NET
libraries such as [Mono][mono], [F#][fsharp], [ServiceStack][servicestack]
easy.


Five minute Summary
-------------------


With Mono-a-mono, you should be able to start into a productive development
environment that has the latest stable versions of the popular Open Source
.NET libraries and frameworks pre-installed.

You will be able to develop on the Mono-a-Mono machine but be able to save
your work to your local file system so that you can integrate better with
local version control and build systems.


What is included?
-----------------

  * Mono -- the latest stable release
  * Fsharp -- the latest stable release
  * Monodevelop with bindings to F#, D and Haxe
  * ServiceStack and related libraries
  * Redis
  * PostgreSQL
  * MySQL
  * nginx
  * GTK#
  * NuGet for Mono 
  * Build system?
  * Packaging?
  * Deploying?
  * Signing?


How does it work?
-----------------

We provide a collection of [Vagrant][vagrant] scripts and chef recipes that are 
will install the base packages for the OS (currently only Ubuntu is planned) and 
other dependencies using [Chef][chef]. 

What will I get?
----------------

You will get a Ubuntu Linux [VirtualBox][virtualbox] that you can `ssh` into locally.
You will be able to run graphical IDEs like [monodevelop][monodevelop].


[mono]: http://mono-project.com/Main_Page
[monodevelop]: http://monodevelop.com/
[servicestack]: http://www.servicestack.net/
[fsharp]: http://fsharp.org/
[vagrant]: http://vagrantup.com/
[chef]: http://www.opscode.com/chef/
[virtualbox]: https://www.virtualbox.org/