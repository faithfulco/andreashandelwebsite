# General
* Any information that applies to this site and handelgroup is not repeated here, see the handelgroup notes file

# To deploy site
push to github. Netlify will automatically build and serve site.
Note that it's important to run build_site() since Hugo/Netlify only do part of the building (they don't process Rmd files)

# Prevent pages from being recompiled
Sometimes I might not want Rmd re-done, e.g. mainly lengthy posts. A hack is to rename them to .Rmdx, which means they'll be ignored by blogdown/rmarkdown. If at another time I want them processed, rename back to .Rmd. Another option is to use `hugo_build` instead of `build_site` but that means no Rmd are processed.

# Ideas for new posts/content

## Science/Research

* Reading/managing/publishing papers: turn my presentation and my text on the 'teaching-research-resources' list into a blog post.


## Teaching/Tech

Review of my technology stack for online courses
  * Github
  * Slack
  * gradingapp
  
* gh_class package to manage class with github and my experience using github for teaching: workflow, exercises

* conceptual thought of usefulness of certain teaching aids like metaphors/examples/jokes that might confuse-enlighten or disengage-engage

* quizgrader description


## Others

* staying mentally in good shape in grad school (and in general)

* comparing mental exercise/meditation to physical exercise, where do analogies work and where do they not
