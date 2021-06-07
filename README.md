# Introduction to Python and Jupyter Notebooks

  ## Installation
  
  Probably the easiest way to get started with Jupyter Notebooks is to install Anaconda. https://www.anaconda.com/ Anaconda includes many Python packages used for scientific computing, including Jupyter Notebooks. Install the version of the Individual Edition suitable for your computer's operating system. https://www.anaconda.com/products/individual (You may need to install Anaconda when you're not behind a firewall.)
  
  ## Introduction to Anaconda Individual Edition and Anaconda Navigator
  
  I would recommend watching the introductory video. https://anaconda.cloud/tutorials/getting-started-with-anaconda-individual-edition?source=individual-edition-tutorial (You will probably need to complete the free registration for Anaconda Nucleus to watch the video.) You don't need to use Anaconda Navigator to use Jupyter Notebooks, but it's a good idea to be familiar with what Anaconda Navigator is. (You may need to use Anaconda Navigator when you're not behind a firewall.)
  
  ## Introduction to Virtual Environments and Package Management
  
  Anaconda comes with a virtual environment and package manager called Conda. The introductory video in the section above gives a nice demonstration of how packages and environments can be managed using Anaconda Navigator. Conda can be used from the command line using the Anaconda Prompt (In Windows Start - Programs - Anaconda3 - Anaconda Prompt), but the graphical user interface of Anaconda Navigator has come a long way and it's probably the simplest thing to use now.
  
  What is a package and an environment? (The TL:DR version) Different projects like computer vision or natural language processing can be accomplished in Python using packages written to accomplish tasks unique to specific kinds of projects. You'll usually only install the specific packages you need for any individual project. However, some packages have different dependencies (versions may change over time), so you may need specific versions of some packages for specific projects. To avoid dependency conflicts between projects, it's useful to put each project in it's own environment. Conda allows you to create new environments which don't interfere with each other and install specific packages in each environment. We can just use the base environment for this demonstration.
  
  ## Introduction to Jupyter Notebooks
  
   ### Start Jupyter Notebook
   * Windows: Start - Programs - Anaconda3 - Jupyter Notebook (Anaconda3)
   * Mac: Open a terminal - navigate to desired folder - type jupyter notebook - hit enter
   * Once you do these, the Jupyter server should start and a browser should open with the Jupyter Notebook in the folder where you opened it.
   
   ### Create a new Jupyter Notebook
   * Jupyter Notebook browser page - New - Python 3
   * A new tab should open with a new notebook
   * You can rename the new notebook by clicking on the title and typing a new name in the popup.

   ### Some commands
   * pwd - (print working directory) Run this command in a cell to see the directory the notebook is saving in.
   * new cell - The plus (+) icon at the top of the page will create a new cell below the cell currently selected. Also available in the Insert menu.
   * Ctrl - Enter will run the code in the cell currently selected.
   * Icons - Hover over icons to see what they do. Try them out.
   * File - Download as 
     * Save the notebook in different formats.
     * .ipynb - Jupyter Notebook file extension
     * .py - Python file file extension
   * Menus - try some out.
   * Cell - Run All
   * Cell - Cell Type - Makrdown
     * Allows you to change the cell to text and formatted text using markdown on your notebook page.

  ## Why use Jupyter Notebooks?
  
  * When you're working on parts of a script, but you don't want to run the entire script to just try out one part.
  * When you're doing some kind of analysis and you want to see the output from a block of code directly under the code.
  * Great for teaching and demonstrations like this.
  
  
