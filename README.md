# README

This repository supports the template for creating OICM using [JupyterBook 2](https://jupyterbook.org/) tailored for the Delft University of Technology (TUD).

## Features
- Including supported plugins
- Pre-configured footer and logos


## 📁 Repository Structure:
├──┐ root  
   ├── plugins.yml          # standard supported plugins   
   ├── style.yml            # making of the template  
   ├── README.md            # this file  
   ├── .gitignore           # files and folders to ignore for synching with git  
   ├── .venv                # secrets  
   ├── requirements.txt     # standard python packages for binder option  
   ├──┐ branding/  
      ├──┐ TUDelft_Logos/   # all TUD standard logos  
         ├── ...            # logos  
      ├── custom.css        # chapter 1  
      ├── favicon.ico       # TUD favicon  
      ├── footer.md         # template footer  
      ├── navbar_end.md     # optional navbar icon  
      ├── tudelft-dark.png  # TUD for top left in dark mode  
      ├── tudelft.png       # TUD for top left  
      ├── JBlogo.svg        # JB logo for footer  
   ├──┐ plugins/  
      ├── iconify.mjs               # allows to include icons, see https://github.com/choldgraf/myst-iconify  
      ├── lightbox.mjs              # creates gallery mode, see https://github.com/myst-contrib/myst-lightbox    
      ├── mainim-widget.mjs         # supports manim plugin  
      ├── mainim.mjs                # manim animation, see https://jupyter-book.github.io/myst-plugins/manim/  
      ├── page-last-updated.mjs     # shows when page has last been updated  
      ├── pdf_exercise.mjs          # supports conversion of exercises to pdf  
      ├── pyodide.mjs               # allows to run editable python code, see https://jupyter-book.github.io/myst-plugins/pyodide-editable/  
      ├── widget.mjs                # supports pyodide plugin      
   ├──┐ scripts/  
   

## 📧 Contact:
For questions about this template, please contact [Reid Sczerba](R.B.Sczerba@tudelft.nl).