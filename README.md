Git repository for a docker image build with `learnr` lessons for different `tidyverse` packages. Developed for general education purposes (statistics and `R`) by P. Lombardo.

So far, this includes:

* A basic ggplot lesson: `ggplot-basics`
* Two lessons on tidy data: 
    * one for identifying untidy data sets `tidy-data`, and
    * another for fixing them `make-tidy`.

Keeping in mind that the `learnr` lesson files must be *locally rendered* to create the .HTML-file before they will work, the docker build runs a script to create these files.
