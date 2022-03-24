# Selectors
A few tricks with selectors

The '*' is the universal selector.  Any property that is within this selector will be changed for everyelement related to it unless overidden with a specific selector

Example
all the text on the page will be black
*{
  color:black;
  }

except for the h1 since it is specified that it will be grey.  This overrides the Universal Selector
h1{
  color: grey;
  }

adding a comma allows you to change multiple elements with only 1 selector
h2,label,p{
  color: darkgreen;
  }
Now all the h2, label and p element text is dark green overriding the universal selector
