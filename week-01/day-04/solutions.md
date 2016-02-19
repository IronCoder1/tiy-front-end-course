##Problem 1

What is the specificity of this selector:

body .warning {
  background-color: orange;
  border: 1px solid rgb(0, 0, 0);
}

it is using element and class selector so it scores 11

## Problem 2

body header p#introduction.important {
  color: red;
  font-size: 150%;
}

this one uses the element , tag, id and class selector so scores 41


## Problem 3

body p p p .welcome.back {
  background-color: blue;
  color: white;
}

using 1 class, 1 sub-class, 3 tags and 1 element = 51

## Problem 4

p {
  color: rgba(277, 60, 0, 0);
}

on screen colors dont go above 255