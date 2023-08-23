Source code for the website of the [APRIL research lab](https://april-tools.github.io) at the [School of Informatics](https://www.ed.ac.uk/informatics), [University of Edinburgh](https://www.ed.ac.uk), UK.

## How to contribute

This site harness Jekyll templates in github pages and their file-based model view.
To add, change or remove a news/lab member/paper on the website, please open a [pull request](https://github.com/april-tools/april-tools.github.io/pulls)!

### Edit lab members profiles

Each member in the lab is associated a markdown file under the `_people` folder. Find yourself there or create a new file.

Mandatory keys in a user profile are:
  - `collection` to be left to `people`
  - `ref` a string acting as a unique identifier _(e.g., `aver`)_
  - `permalink` a url in the form `people/{ref}`
  - `name` your full name
  - `role` your role in the lab _(e.g., `PI`|`PhD Student`|`Visitor`|`Postdoc`|`MRes Student`|`Research Assistant`)_
  - `date` proxy date (used to order people in the grid)
  - `webpage` your webpage url
  - `image` url to profile pic (can be stores in `images/people/`)

  Optional keys are:

  - `affiliation` used for visitors/interns
  - `firstsupervisor`, `secondsupervisor` and `cosupervisor` to specify your supervisory team

### Edit papers

Each paper listed in the website is associated a markdown file under the `_publications` folder. Simplest way to add a paper is to duplicate an already-existing entry and modify the values associated to the keys there.

Mandatory keys in a paper description are:
  - `collection` to be left to `publications`
  - `ref` a string acting as a unique identifier _(e.g., `vergari2021atlas`)_
  - `permalink` a url in the form `publications/{ref}`
  - `title` the complete paper title
  - `date` intended as a publication date (used to order papers)
  - `tags` a space-separated sequence of tags to classify the paper
  - `authors` a string with authors names, separated by comma
  - `venue` the publication venue (conference | journal name and year)
  - `paperurl` a webpage for the paper (can be the same as `permalink`)
  - `excerpt` a two-line summary of the paper

Optional keys are:
  - `image` link to a small preview image (you can upload it under `images/papers/{ref}`)
  - `pdf` link to a publicly readable version of the paper
  - `supplemental` link to the paper supplemental material
  - `code` link to the code released with the paper
  - `poster` link to the paper poster
  - `video` link to the paper video presentation or relative talk
  - `abstract` the paper abstract, as a single string
  - `bibtex` a string for the bibtex entry (mind to put `<br/>` tags for newlines)
  - `spotlight` a large image, to be used if the paper has to be features in the homepage (you can upload it under `images/papers/{ref}`)

  Additionally, you can write a free-form blog post about the paper in the markdown `content` section.

  ### Edit news
  
  Each news is associated a markdown file under the `_news` folder.

  Mandatory keys in a paper description are:
  - `collection` to be left to `news`
  - `permalink` a url in the form `news/{short-handle}`
  - `title` the news title
  - `date` date of the news (used to order news)  

  The body of the news can be written in html/md in the markdown `content` section.
