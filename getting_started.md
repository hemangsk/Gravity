Gravity is a minimalistic theme for [Jekyll](https://github.com/hemangsk/Gravity). This guide shall provide a concise and 
step-by-step guide to using Gravity as your blog's theme.


## Contents

- [Installation] (#installation)
- [Usage] (#usage)

## Installation

### Dependencies

Gravity uses Jekyll and it's built-in SCSS compiler for the associated CSS, so the first thing you'll need is Jekyll itself:

```bash
$ gem install jekyll
```

In case you don't have the `bundler` gem installed already, you can install it as follows:

```bash
$ gem install bundler
```

For pagination, Gravity uses the [jekyll-paginate](https://jekyllrb.com/docs/pagination/) gem :

```bash
$ gem install jekyll-paginate
```

## Usage

Once you have the required gems, you can go ahead and clone the 
[Gravity repository](https://github.com/hemangsk/Gravity) or [download](https://github.com/hemangsk/Gravity/archive/master.zip)
a zip of the master branch.

Run :

```bash
$ jekyll serve
```
Jekyll should now be generating your content! 

### Adding posts

The theme by default ships with starter posts located in `_posts/`. Delete these posts and add your content to the `_posts` 
folder to see them being served up by Jekyll. [This](https://jekyllrb.com/docs/posts/) would be a good guide to getting started
on writing posts using Jekyll.

Happy blogging!




