# riotjs_wiki
riot.js Learning for an AngularJS guy


###Communication with tags

SubTags are mounted automatically

To communicate with subtags, you need to mount them manually

    this.on('mount', function(){ //parent tag
      tags.navbar = riot.mount('#navbar')[0]; //child tag
     }

Afterwards you can emit events to tags

    tags.navbar.trigger('hello', param);


### Sample Tags

Timer
http://jsfiddle.net/gnumanth/h9kuozp5/
