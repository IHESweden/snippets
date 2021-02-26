# snippets

Requires installation of the snippr package, which may in turn requires installation of Devtools

devtools::install_github("dgrtwo/snippr")

library(snippr)

You can then download and install the strucutre snippet with the command

snippets_install_github("dgrtwo/snippets", language = "r", name = "structure")

After installation which only is needed once you can open a blank r document, start typing "new" and the snippet name "new_script" should show.
Press tab and the layout will be sorted for you
