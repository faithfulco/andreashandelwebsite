# General
* Any information that applies to this site and handelgroup is not repeated here, see the handelgroup notes file

# To deploy site
push to github. Netlify will automatically build and serve site.
Note that it's important to run build_site() since Hugo/Netlify only do part of the building (they don't process Rmd files)

# Prevent pages from being recompiled
Sometimes I might not want Rmd re-done, e.g. mainly lengthy posts. A hack is to rename them to .Rmdx, which means they'll be ignored by blogdown/rmarkdown. If at another time I want them processed, rename back to .Rmd.

# Ideas for new posts/content
* MADA online course setup/experiences (mention 'date changed in yaml')
* gh_class package to manage class with github
* general github workflow for classes
* conceptual thought of usefulness of certain teaching aids like metaphors/examples/jokes that might confuse-enlighten or disengage-engage
* staying mentally in good shape in grad school (and in general)
* making certificates with RMarkdown


