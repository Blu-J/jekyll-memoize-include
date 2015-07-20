# What does it do

* Memorizes the include, which means that we can cache calculated includes
* Great for templates that don't have the many different parameters and is pure in the sense that it is modified only by parameters

# How to use
* Clone the repository
* Copy the mem-include.rb into _plugins
* use `{% meminclude test.html param1="1234" %}` instead of `{% include test.html param1="1234" %}`


