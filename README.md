# boneWidget

2.7 explanation : https://vimeo.com/184159913

----------
2.8 list of bugs/todos:
-Symmetrise not yet working

-add property to be able to rotate the widgets
-add function to clear widget from bone
-add operator to show/hide the collections
-add operator that will resync the names of the wdgts to the bones
(sometimes you change them so it would be a nice feature)

-it doesn't delete the _old widget_ when creating a new one

-at the moment it will only match the bone matrix when the armature is at a scale of 1.0  This is because the old id_data used to point to the object, but now it points to the data object.
I need to think about how to solve this.

-improve the ui
