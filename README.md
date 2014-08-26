#Ember.js Touch Helpers
=============

##ember-fastclick.js
Allows you to use a view's click function or {{action}} in a touch enviroment without the 300ms delay.
Elements have the name 'pseudo-active' while being touched. Normal active state doesn't work.

##Local Modifications
* Ignore form elements
* Bring up to current ember _setupHandler code
* Do not add pseudo-active class (performance)
