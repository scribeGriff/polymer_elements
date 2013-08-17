## Porting Polymer Elements to Dart ##
[Reference: Polymer Toolkit UI](https://github.com/Polymer/toolkit-ui/tree/master/elements)

Note: At this point, I'm having a hard time determining if I am doing something wrong or if there is something missing from Polymer.dart.  Hopefully that will start to improve in the not too distant future.

### Issues: ###

- Unable to pass a style attribute to an element.
- When to use ChangeNotifierMixin instead of ObservableMixin?
- Unable to apply most styles or attributes of an element.

This does not work (the elements still do not have background images):

    <g-icon src="elements/images/star_full.png"></g-icon>
    <g-icon-button src="elements/images/star_full.png"></g-icon-button>
    <script type="application/dart" src="polymer_elements.dart"></script>

### Elements: ###

- g-icon - binding to style attribute not implemented yet?
- g-icon-button - same issue as g-icon 
- g-field
- g-form
- g-checkbox

