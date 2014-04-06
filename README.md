# Zrcadlo Scripture

Herein we have a repository to ultra-nerdly manage the unholy canon of Zrcadlo. It uses a series of convoluted technologies that I will endeavor to explain below.

## Setting this shiz up

1. To preview or re-build the site, you need to have ruby installed. On a mac, a sane version of ruby should be already provided for you (`ruby -v` will output the version, anything >= 1.9.3 should be fine). 
2. (Optional) if you have more than one ruby project in your local machine, it's recommended to sandbox this one to not pollute your global namespace; consider using [RVM](http://rvm.io/rvm/install) for that purpose.
3. Install jekyll: `gem install jekyll` (more info at the [jekyll site](http://jekyllrb.com/))
4. Clone the repo from github: `git clone git@github.com:zrcadlo/zrcadlo.github.io.git`
5. If jekyll is installed properly, you should be able to just run `jekyll serve` and navigate to [localhost:4000](localhost:4000) to see the site.
6. 66; the number of the beast!

## Adding posts

To add a post, simply add a new file to the `_posts` directory following the following naming convention: `YEAR-MONTH-DAY-title.markdown` (the extension can also be `.textile`). 

The convention is to use [](markdown) for editing posts; given the simplicity and visual feedback, it doesn't need fancy editors. However, I've used [vim](http://www.vim.org/) with markdown syntax highlighting and [Mou](http://mouapp.com/) in the past. 

## Customizing

The base of the customization lays in the layouts (within the `_layouts` folder), and uses [Liquid](http://wiki.shopify.com/Liquid) templates to add dynamic elements. More info on customizing can be found in the official [jekyll documentation](http://jekyllrb.com/docs/templates/). 


## Reference

* [Jekyll](http://jekyllrb.com/)
* [Lanyon](https://github.com/poole/lanyon), which is the base theme chosen for this site. It's, oficially, a theme for the [Poole](https://github.com/poole/poole) jekyll wrapper.
