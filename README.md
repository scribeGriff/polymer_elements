## Porting Polymer Elements to Dart ##
[Reference](https://github.com/Polymer/toolkit-ui/tree/master/elements)

### Issues: ###

- Unable to pass a style attribute to an element.
- When to use ChangeNotifierMixin instead of ObservableMixin?

This does not work (the elements still do not have background images):

    <g-icon src="elements/images/star_full.png"></g-icon>
    <g-icon-button src="elements/images/star_full.png"></g-icon-button>
    <script type="application/dart" src="polymer_elements.dart"></script>

### Elements: ###

- g-icon - binding to style attribute not implemented yet?
- g-icon-button - same issue as g-icon 

