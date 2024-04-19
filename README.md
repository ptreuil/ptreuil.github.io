# The PTREUIL website

## Existing work

* Several pages filled with texts
* An highly customised configuration
* light/dark mode switch
* Extensive research option
* French translation
* PDFs download toggled

## TODO LIST

* [x] French translation
* [x] Dark mode
* [ ] Blog
* [ ] LaTeX project
* [ ] French/English CV
* [ ] Think to the next todo list

## How to use

1. Install the requirement in a nice conda environment

       conda create --name env --file requirements.txt

*/!\ This requirement.txt file is not suitable for ``pip install`` and is not currently properly cleaned. If you use an other environment name than ``env`` please, add it to the ``.gitignore``.

1. To run the site locally

        mkdocs serve --watch-theme 

2. To deploy on GitHub

        mkdocs serve --watch-theme 


**Final notes:** Setting a project like that was not that hard but the documentation is lengthy, you can do a lot if you take time to read all the docs, if you want to do the same, please have fun !