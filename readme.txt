Updating Forum Icons

Load the themes global.css and locate .ficons (best way is by CTRL + F and then CTRL + V).
Once you have the .ficons you'll see something similar to the following;

.ficons_2 i:before {
content: "\f0a1";
}

.ficons_4 i:before {
content: "\f0c0";
}

.ficons_5 i:before {
content: "\f0f5";
}

.ficons_6 i:before {
content: "\f0e4";
}

Update the number at the end (.ficons_2) to be your forums ID. E.G. 6,24 etc.
To change the icon go here; http://fontawesome.io/icons/
Choose an icon and on it's page get the 'Unicode' and update it in "\f0e4";
Save and the icon will change. If it has not do a hard refresh (CTRL + F5).