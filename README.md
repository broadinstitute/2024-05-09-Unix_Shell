# Session website for 2024-05-09 The Unix Shell (pilot)

This repository is based on The Carpentries' ([Software Carpentry][swc-site], [Data Carpentry][dc-site], and
[Library Carpentry][lc-site]'s) (template)[https://github.com/carpentries/workshop-template] for creating websites for workshops. This IS NOT the [session content](https://jlchang.github.io/2024-05-09-Unix_Shell_pilot/] [github](https://github.com/jlchang/2024-05-09-Unix_Shell_pilot).

View the [session website](https://broadinstitute.github.io/2024-05-09-Unix_Shell/)


1. **Please _do not fork this repository directly on GitHub._** Instead, please use GitHub's
   "template" function following [the instructions below](#creating-a-repository) to copy this
   `workshop-template` repository and customize it for your workshop.

2. Please *do your work in your repository's `gh-pages` branch*, since that is what is
   [automatically published as a website by GitHub][github-project-pages].

The pages on [customizing your website][customization],
the [FAQ][faq],
and the [design notes][design] have more detail on how this template works and why.
And please note:
if you are teaching Git,
please [create a separate repository](#setting-up-a-separate-repository-for-learners)
for your learners to practice in.

## Video Tutorial

There is a [YouTube video](https://www.youtube.com/watch?v=_Ag1JiZzyUQ) that demonstrates how to
create a workshop website.


### Working locally

> Note: you don't have to do this, if you have already updated your site using the web interface.
> This may be more efficient if you are making interdependent changes in multiple files
> (or create a branch using the web interface before making interdependent changes and merge to `gh-pages`)


If you are already familiar with Git, you can clone the repository to your desktop, edit `index.md`,
`_config.yml`, and `schedule.html` following the instruction above there, and push your changes back to the repository.

```shell
git clone https://github.com/your_username/YYYY-MM-DD-site
```

In order to view your changes once you are done editing, if you have bundler installed (see the
[installation instructions below](#installing-software)), you can preview your site locally with:

```shell
make serve
```
and go to <http://0.0.0.0:4000> to preview your site.

Before pushing your changes to your repository, we recommend that you also check for any potential
issues with your site by running:

```shell
make workshop-check
```

Once you are satisfied with the edits to your site, commit and push the changes to your repository.
A few minutes later, you can go to the GitHub Pages URL for your workshop site and preview it. In the example above, this is `https://gvwilson.github.io/2016-12-01-oomza`. [The finished
page should look something like this](fig/completed-page.png?raw=true).


[customization]: https://carpentries.github.io/workshop-template/customization/index.html
[dc-site]: https://datacarpentry.org
[design]: https://carpentries.github.io/workshop-template/design/index.html
[faq]: https://carpentries.github.io/workshop-template/faq/index.html
[github-project-pages]: https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site
[issues]: https://github.com/carpentries/workshop-template/issues
[lesson-example]: https://carpentries.github.io/lesson-example/
[self-organized-workshop-form]: https://amy.carpentries.org/forms/self-organised/
[swc-site]: https://software-carpentry.org
[lc-site]: https://librarycarpentry.org
