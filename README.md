Paper Fab Menu
================


Paper Fab Menu provides a Floating Action Menu, displaying sub-actions with optional labels that are triggered by a main action `paper-fab`

## Download

To get the `paper-fab-menu` component, run the following command:

    bower install --save faizmalkani/paper-fab-menu
    
    
    
## Import
    
Once the dependencies are resolved, close the command window, open up the file you want to add the `paper-fab-menu` to, and import the component within the `<head>` tag somewhere after importing the Polymer script, like this:

```html
   <link rel="import" href="bower_components/paper-fab-menu/paper-fab-menu.html">
```   
    

## Use
    
That's it! To use the component, add `<paper-fab-menu></paper-fab-menu>` within the `body` tag, and include numerous `paper-fab` elements within it, the number being *Number of Actions + 1*, with the extra `paper-fab` acting as the trigger.
Once included, add the *trigger* attribute to the last `paper-fab` and the *mini* attribute to the rest of them. Optionally, you can also provide descriptions for the actions using `<span></span>`. The layout should look something like this:
    
```html
<paper-fab-menu>
    <span>Description</span>
    <paper-fab mini icon="description"></paper-fab>
    <span>Extension</span>
    <paper-fab mini icon="extension"></paper-fab>
    <span>Polymer</span>
    <paper-fab mini icon="polymer"></paper-fab>
    <span>Folder</span>
    <paper-fab mini icon="folder"></paper-fab>
    <paper-fab trigger icon="add"></paper-fab>
</paper-fab-menu>  
```
