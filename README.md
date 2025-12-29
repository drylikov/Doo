
## Just Doo It

Doo is an experiment in taking a relentlessly polymorphic approach to deployment scripting. Like most deployment tools, doo lets you define executable blocks of deployment code independent of the configuration particulars that get bound into them at runtime. Where doo is different is in its succinctness (its core is just shy of 100 LoC), and in its use of polymorphism to realize stacking contexts. This lets you do useful things like defining configuration parameters on a project-wide, server-specific, and even task-specific level without having to rewrite (or doctor the hell out of) your deployment code.

Because executable blocks are also polymorphic, you can mix and match provider blocks into your recipes. Want to have one deployment recipe for local and remote targets? No problem. Want to abstract away the particulars of your server's OS? We can do that, too.
 
Doo layers a thin DSL that facilitates polymorphic behaviour on top of bare Ruby, and leans on a small number of built-in (and optional) deployment recipes to provide useful functionality.

## Play With It

    gem install doo

Check out examples/sample.rb to get started.






































