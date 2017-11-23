## Core Concept

This is a Jekyll Application created to build www.coreconcept.pt's website.

### Requirements

- Ruby 2.4.2
- Jekyll 3.6.2

### Development

1. `git clone git@github.com:simaob/core_jekyll.git`
2. `cd core_jekyll`
3. `bundle install`
4. `jekyll serve`
5. Point your browser to the address shown and then code away. The content will
update automatically.


### Deployment
1. From the project root directory `jekyll build`
2. Copy the contents of folder `_site` to your web server and that's all you need

### Data

The main bits of data are `tags` and the list of `projects`, you can find both
on the `_data` folder inside `yml` files. Projects' cover images are stored in
`img/core/projects`, so you only need to refer to the file name in the data file.
