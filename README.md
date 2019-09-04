![Flastik Icon](https://github.com/theelectricbrain/Flastik/blob/master/flastik/base_templates/default_icon.png)
# Flastik
Flastik is a tiny-framework for static website design inspired 
by Flask micro-framework. It provides tools for designing simple 
static website project using Flask-like syntax and project 
architecture as well as leveraging Jinja2 templating system and 
Bootstrap "beautyfying" capability. Additionally, Flastik aims 
to ease the porting to Flask if extra functionality becomes needed 
further down your website life cycle. 

In addition, classes and functions have been designed in order to 
ease the management and templating of images, downloads and other 
static files (see StaticFile, Image and Download classes as well as 
collect_static_files function).

## Installation
In order to install Flastik:
 * Change directory to the FlastiK code base
 * Run “pip install .”, or “python setup.py install” if you don’t 
   have pip installed on your work station, to install the package 
   (or “sudo python setup.py install”/”sudo pip install .” if root 
   permission is required)
 * Finally run “python setup.py test”  to test the sanity of the 
   package installation (or “sudo python setup.py test” if root 
   permission is required)

## Usage
Once Flastik installed, run "flastik --create_doc" from a command
line in order to have access to more detailed documentation.

Similarly, to start up a new flastik prioject, run "flastik 
--create_project PROJECT_NAME" from a command line.