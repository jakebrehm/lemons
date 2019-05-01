# Lemons

A package that makes things easy.

## Why lemons?

Originally intending to call this package *ezpz*, it was soon discovered that the name was already taken. Heartbroken, and with no other ideas for what to call this package, it felt like the world had ended.

Then I had the idea: why not go back to the root of it all, the title of one of my earliest programs: *EZPZ Lemon Squeezy*. When life give you lemons, you squeeze them! A simple yet elegant title was there all along, yearning to represent this package; thus, the name *lemons* was born.

## What does it do?

*Lemons* tries to make data crunching and GUI building easier by eliminating a lot of repetitive and error-prone code. Please keep in mind that the package is still in its infancy, so its functionality is currently quite limited.

### Data Crunching

With one line of code each, *lemons* can currently:

* Read a .csv file and return the desired columns
* Write data to a .csv file
* Separate the header of a data set into header data and body data
* Combine the header data with the body data again if necessary

### GUI Building

The tkinter framework, as many know, is not the most user-friendly GUI-builder out there. *Lemons* hopes to help ease that pain a little. This is the are where this package really shines.

Some of the things that can be done:

* Easily create a horizontal separator with vertical padding
* Add convenient spacing between widgets
* Make input and output fields and lists, and then easily get the filepaths of the selections
* Creating a scrollable notebook tab, which previously took dozens of lines of code per tab, can now be done in just two.

        tab = lemons.gui.ScrollableTab(notebook, 'Title')
        # Your tab contents here
        tab.update()