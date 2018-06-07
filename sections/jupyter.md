The [Jupyter](http://jupyter.org/) notebook is an open source semi language agnostic programming development environment aimed at simplifiying the creation and sharing of documents that contain live code, figures, and explanatory text. The Jupyter package is installed by default as part of the [Anaconda](python.md) environment and can be updated using the [conda](conda.md) package management system. 

## Executing Code in a Notebook
1. To open a jupyer notebook, first open a [windows](windows_terminal.md) or [OSX](osx_terminal.md) terminal. 

2. Via the command line, navigate to the folder in which  you would like to open the notebook. 

3. Then type the following in your terminal:
```bash
jupyter notebook
```

4. In your default web browser (e.g. Firefox, Chrome, or Safari), you should now see a window that looks like this.
![jupyter notebook homescreen, which is a list of folders and files in the directory in which the notebook was opened](../images/osx/jupyter/notebook01.png)

5. To open a new notebook, navigate to the `New` drop down menu in the upper right corner and select `Python 3` from the new menu. 

![notebook with new menu selected and options listed: Python 3, Text File, Folder, Terminal ](../images/osx/jupyter/notebook02.png)

6. This is what an empty Jupyter notebook looks like: 
![empty jupyter notebook with menubar across the top: file, edit, view, insert, cell, kernel, widgets, help. Below the menu is an empty code block](../images/osx/jupyter/notebook03.png)

7. Rename the notebook by *clicking* on the `Untitled` at the top of the page. That will spawn this window:

![rename window with text box to enter new name and cancel and rename buttons](../images/osx/jupyter/notebook04.png)

8. The light gray boxes are Python interpreter cells in which code can be executed. Here, we write the code `print("hello world"))`. 

![light gray code cell with print("hello world") in it](../images/osx/jupyter/notebook05.png)

9. To run the the code, we press `<shift>` + `<enter>`. The results are printed in the white cell underneath the code cell.

![light gray code cell with print("hello world") in it, "hello world" printed out on white underneath](../images/osx/jupyter/notebook06.png)

10. After a cell is executed, Jupyter notebook automatically adds a new cell underneath:
![Annotated screenshot where the code and output cells are labeled. New cell underneath highlighted in green.](../images/osx/jupyter/notebook07.png)

## Cell Menu

A Jupyter notebook consists of cells. Each cell can contain code or text. The menubar for managing these cells is at the top of the notebook under the file menu. Hovering over the menu items yields their function. The menubar looks like this:
![jupyter notebook cell menu: save, add, cut, copy, paste, move up, move down, run, stop, restart, restart+play, cell type](../images/osx/jupyter/cells/cell_menu.png)

icon | function
---- | --------
![floppy disk](../images/osx/jupyter/cells/cell_s.png) | save the notebook
![plus sign](../images/osx/jupyter/cells/cell_a.png) | insert cell below
![scissors](../images/osx/jupyter/cells/cell_d.png) | cut the selected cells
![one dog eared paper on top of another ](../images/osx/jupyter/cells/cell_c.png) | copy the selected cells
![dog eared paper on top of blank paper](../images/osx/jupyter/cells/cell_p.png) | paste the selected cells
![up arrow](../images/osx/jupyter/cells/cell_up.png )| move selected cells up
![down arrow](../images/osx/jupyter/cells/cell_down.png) | move selected cells down
![play button (triangle facing straight line) + word `run`](../images/osx/jupyter/cells/cell_run.png) | execute code in cell
![stop button (square)](../images/osx/jupyter/cells/cell_stop.png) | terminate execution of cell
![rewind button (looping arrow)](../images/osx/jupyter/cells/kernel_restart.png) | restart notebook
![fast forward button (two arrows)](../images/osx/jupyter/cells/kernel_restart_run.png) | restart notebook and execute all cells
![drop down menu with variable options about cell type depending on what plugins are installed](../images/osx/jupyter/cells/cell_type.png) | type of cell (e.g. code, markdown, raw, etc)

Jupyter notebook also provides a set of keyboard shortcuts for managing these cells. You can read more about them at http://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Notebook%20Basics.html#Keyboard-Navigation