# event-utility

JavaScript Event Utility - props to Jeremy McPeak of tuts+

A very simple cross-browser JavaScript event utility; for those of you who do not wish to include a JavaScript library, such as jQuery, etc. . 

An object with the following methods:

- addEvent: used to add an event
- removeEvent: used to remove an event
- getTarget: used to get the target of an event
- preventDefault: prevent the default action of an event
- getCharCode: get the character code of e.g. a keypress event


Usage
-----
Simply include this file at an appropriate place within your html. 

e.g. 
```
<DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <p>My page contents...</p>
    
    ...
    
    <script src="event-utility.js"></script>
    <script src="script.js"></script>
  </body>
</html>
```

