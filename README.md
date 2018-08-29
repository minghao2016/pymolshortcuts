# pymolshortcuts
The repository ***pymolschortucts*** contains over 200 functions mapped to short-names that work like aliases. 
These shortcuts include many convienence functions that make work in PyMOL more productive.

For example, the shortcut **PW** takes one or more search terms and the sends them to the PyMOL Wiki.
A browser tab opens for each search term, so multiple searches are run in parallel.
Other search functions can submit parallel searches of PubMed, google, bioRxiv, ResearchGate, GitHub, and so on.

Another class of shortcuts saves files with timestamps embedded in the filename to avoid overwriting png, pdb, pse, and other types of files written out from PyMOL. These save function names begin with **s**, e.g., **spse filename** saves the current session with a timestamp embedded in the file name. You can delete the unwanted version at a latter time. These functions are useful if you do not have these files under version control.          

The functions are stored in a single file: pymolshortcuts.py
Add the command 'run ~/pymolshortcuts.py' to your pymolrc or pymolrc.pml to load the functions in pymolshortcuts.py on startup of PyMOL.
In spite of the command *run*, the functions will be loaded into memory but not executed.
Enter **SC** to get a list of shortcuts printed to the command history window.
Enter **help PW** to have the documentation for the function **PW()** printed to the command history window.
 
Videos that demonstrate representatives from each class of shortcut are planned. 
