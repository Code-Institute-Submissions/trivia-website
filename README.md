# QI | The Interactive Trivia Game

The project is based on the popular and renowned BBC panel-show, QI (Quite Interesting).

# UX 

## Wireframes

- [Wireframes for desktop and tablet](assets\images\wireframes\Desktoptrivia.pdf)
- [Wireframes for Android, both vertical and horizontal modes](assets\images\wireframes\Triviamobile.pdf)

# Optimization

## Graphics
To optimize the svg-files, I used https://svgomg.firebaseapp.com/. Each svg-file was reduced by 9%-70%, as a result saved memory space.

## Browser compatibility

Troughout the project, I've tried to manage my code to be able to work on as many 
browsers as possible. However, in some cases due to time-management, focus has been 
put on the larger browsers. As of Febuary 2020, Chrome is the most frequently used 
browser globally at 58,1%. Safari: 13%, IE and Edge: 12.9%, Firefox: 5,4% and Opera 2.7%.

* Internet Explorer and Edge (updated 04/15/2020):
    * Fetch: At the moment, fetch () is compatible with Edge, but not with IE.
    However, as IE is getting phased out into Edge, I decided to still use it instead of,
    XMLHttpRequest for instance.
    * Flex: Not supported by IE 6-9, partially supported by IE 10-11 and supported by Edge.