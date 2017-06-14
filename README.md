pydown

pydown is another "Presentation System in a single HTML page" written by python inspired by keydown.

Like keydown it uses the deck.js and its extentions for the presentation.

Demo

http://isnowfy.github.io/pydown/

Usage

Write your slides in markdown

Edit slides.md

!SLIDE

# Hello

!SLIDE

# Another slide

!SLIDE left

# left
Generate the html

$ python main.py slides.md slides
or you can install pydown to run it with pydown

Thanks for sloria

$ pip install python-pydown
$ pydown slides.md slides
This will make:

| - slides/
  | - css/
  | - js/
  | - index.html
Slide classes

Any text follows !SLIDE will be added to the slide as css classes

!SLIDE left
Syntax Highlighting

For python

~~~~{python}
   def test():
       print 'hello'
~~~~
Markdown syntax

English version

Chinese version
