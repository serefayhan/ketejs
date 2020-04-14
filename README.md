# KeteJS
KeteJS is simple and very very little "into the middle" javascript templating engine.

_(At least, we think this way about that)_

# Usage
JSFiddle Demo: https://jsfiddle.net/07og9zh3/


load kete.js in <head /> tag.

define a template. To place variables into the template, write variable names between curly brackets 
var template= "Hello {name}!";

prepare data to mix in template
var data = { 
  name: "Jack"
}

shake and bake!
var greetings = Kete(template, data);

use in anywhere
document.getElementById("header").innerText = greetings;

