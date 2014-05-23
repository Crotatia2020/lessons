Lessons
=======

This repository contains the teaching materials used by the Research Bazaar.  

The directory prefix "swc" indicates that the materials are taken largely from 
[Software Carpentry](http://software-carpentry.org/), which is a volunteer organisation that
teaches programming skills to researchers.    

There are a number of Software Carpentry lessons that are currently being developed that we would be interested in including in our courses:  

* IPython parallel intermediate lesson (see [lesson](https://github.com/cfriedline/bc/blob/swc-ipython-parallel-lesson/intermediate/python/05-ipython-parallel.md) and [pull request](https://github.com/swcarpentry/bc/pull/438/files))
* Python spatial mapping novice lesson (see [pull request](https://github.com/swcarpentry/bc/pull/387))
* Make intermediate lesson (see [lesson](https://github.com/swcarpentry/bc/tree/master/intermediate/make))
* Python multiprocessing intermediate lesson (see [lesson](https://github.com/swcarpentry/bc/blob/master/intermediate/python/04-multiprocessing.md))

Note that the materials in the Software Carpentry [bc repo](https://github.com/swcarpentry/bc) are organised as follows:  

* The `gh-pages` branch has the complete, mature materials
* The `master` branch has materials that are still being refined, but are good enough to use as they are
* All other development is tracked via [issues](https://github.com/swcarpentry/bc/issues) or [pull requests](https://github.com/swcarpentry/bc/pulls)


### Contributing new material

If you'd like to contribute new lesson material or make edits to existing lesson materials in any of the "swc" labelled directories, then it's best to do that at the Software Carpentry ["bc" repo](https://github.com/swcarpentry/bc) (i.e. we just keep a clone of their matertials here because their repo can be a little confusing to navigate for newcomers). A video lesson on how to contribute to their repo can be found [here](http://vimeo.com/92273942).  

If you'd like to contribute new matieral to our lessons repo (i.e. materials that are not associated with Software Carpentry), follow these steps:  

1. [Fork](https://help.github.com/articles/fork-a-repo) the lessons repository.
2. Create a new [branch](https://github.com/resbaz/lessons/blob/master/git/swc-intermediate/02-branching.md) and make all your changes/edits on that branch (i.e. do not make your changes on the `master` branch, as this makes it difficult to merge later on). If your edits are for a particular discipline and bootcamp, make that explicit in the branch name (e.g. `2014-02-30-meteorology-bootcamp`).
3. Once you're done, submit a [pull request](https://help.github.com/articles/using-pull-requests) and we'll review your changes.

### Bootcamp resources

Software Carpentry has a very detailed [operations guide](http://software-carpentry.org/bootcamps/operations.html) for running bootcamps, in addition to an [instructional video](http://vimeo.com/87241285) on how to create a bootcamp website. 
