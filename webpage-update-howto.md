The workshops web page of the BBOB series is automatically generated from restructured text. This
document explains briefly how to update it.

HowTo: Edit the BBOB workshop series webpage
--------------------------------------------
The source files (as reStructuredText) of the workhop web page can be found and edited in the subfolder `sources-webpage/`.
The source files' reStructuredText is
translated into html, latex, or pdf with the help of Sphinx (http://www.sphinx-doc.org). To build the html, latex, or pdf
output for each documentation, you need to install sphinx by typing `pip install -U Sphinx` (if you have installed pip) and then
type `make html`, `make latex`, or `make latexpdf` directly in the folder sources-webpage/. The output will be written into
the corresponding subfolder of the `build/` folder and will not be included in any repository.


HowTo: Publish the BBOB workshop serires webpage
------------------------------------------------
For publishing the html output to the web, a `make html-topublish` in the folder `sources-webpage/` will create the
same html files than `make html` but instead of the build/ subfolder, it uses the correct folder to be published
directly on the webpage. To make this actually happen, the changes made have to be pushed to the only branch called
`gh-pages` by a simple `git push` command in the root of this github repository. Due to the git pages functionality,
the push will directly update the web page.



#### Summary:
- need: python, sphinx, git
- edit `.rst` sources in `sources-webpage/source/` and commit and push as usual within the only existing branch `gh-pages`
- for checking the output, type `make html`, `make latex`, or `make latexpdf` (output written to build/ subfolder)
- for publishing the changes to the web:
  - create the html with `make html-topublish`
  - commit and push the changes (in the `gh-pages` branch) to update the web page