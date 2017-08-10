# Git-Up-to-Speed

This is a course created for [WeAllJS.org](http://wealljs.org) for the August 2017 meetup.

You can view the course website at [bit.ly/wealljs-aug17](bit.ly/wealljs-aug17)

## Contribution Instructions
Here are the steps that should be taken on all contributions.

* **Submit an issue for edits and removes changes to be made**
    * `ADD` additions to the site
    * `EDIT` changes to existing content
    * `REMOVE` delete old content (not replaced)

* **Work on your own branch outside of master beginning with your initials**
  * ex: `jm-add-some-page`

* **Rebase your code and ensure it's up to date before submitting a pull request.**
  This will handle all conflicts on your end and not on `origin/master`

* Your code will be merged for you by a contributor.

## Known Issues (and Solutions)
### CSS doesn't work if not using GH-Pages or the subroot folder Git-Up-to-Speed  

This was mostly due to GitHub having an assets folder that you can't modify easily with the base with the base `gh-pages`.

**Possible Solutions**
This code may be converted to a pelican page or jekyll page to resolve the issues later on if demand for the page is requested.

Until then, *test* css links have been added in the headers of each page.

### Relative Links don't work if testing without the .html suffix
This is due to a lack of web services running.

 **Solution**
 append the `.html` suffix to your relative urls.
