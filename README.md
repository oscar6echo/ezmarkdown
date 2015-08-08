###ezmarkdown

**ezmarkdown** stands for easy MarkDown.

[MarkDown](http://en.wikipedia.org/wiki/Markdown) is a convenient way to write formatted documents.  
It was created with the goal of enabling people to "to write using an easy-to-read, easy-to-write plain text format, and optionally convert it to structurally valid HTML".  
See [this cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).  

This module enables to write MarkDown in an IPython notebook and export some or all the cells in the notebook as a standalone HTML document.  

The export module uses nbconvert.  
Several export templates are available:
+ Output cells only
+ Input cells only
+ Input and output cells
+ Output cells with toggle input cells
+ Input cells with toggle output cells

See the [example notebook](https://github.com/oscar6echo/ezmarkdown/blob/master/demo_ezmarkdown.ipynb)

To install run from command line:  
```
pip install ezmarkdown
```
