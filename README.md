<p align = "center">
<img src="http://i.imgur.com/JhbQ03z.png"/>
</p>

---

If there's any issue you are facing in setting up this theme I'm there for you. Just create an issue in this repository (<http://github.com/hemangsk/Gravity>), (<https://help.github.com/articles/creating-an-issue/>) and I'll get back to you asap.

![Welcome to Gravity](https://user-images.githubusercontent.com/13018570/27043040-778d80cc-4fb6-11e7-8619-de4be626be67.png)
<img src="http://i.imgur.com/cPwoX3E.png"/>
<img src="http://i.imgur.com/3TMoBGj.png"/>
<img src="http://i.imgur.com/Z6h3uCp.png"/>
<img src="http://i.imgur.com/bB7IIHr.png"/>

***

# INSTALLATION

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

***

# USAGE

Once you have the required gems, you can go ahead and clone the
[Gravity repository](https://github.com/hemangsk/Gravity) or [download](https://github.com/hemangsk/Gravity/archive/master.zip)
a zip of the master branch.

Run :

```bash
$ jekyll serve
```

Jekyll should now be generating your content!

***

# ADDING POSTS

The theme by default ships with starter posts located in `_posts/`. Delete these posts and add your content to the `_posts`
folder to see them being served up by Jekyll. [This](https://jekyllrb.com/docs/posts/) would be a good guide to getting started on writing posts using Jekyll. We've added a concise guide below:

- Create a .markdown file inside `_posts` folder.
- Name the file according to the format YY-MM-DD-[short name for your post].
- `2016-03-30-i-love-design.markdown`
- Write the *Front Matter* and content in the file.

### FORMAT

```
---
layout: post | default | page
title: String POST TITLE
date: Time Stamp
categories: String | Array of Strings CATEGORY / CATEGORIES
---

---
layout: post
title: "The One with the Blackout"
date: 2016-03-30 19:45:31 +0530
categories: ["life", friends]
---
```

***

# CREATE PAGES

- Create a .md file in the root directory.
- Name the file with the desired page link name.
  `about.md`
  `design.md`
- Write the *Front Matter* and content in the file.

### FORMAT

```
---
layout: page
title: String TITLE OF THE WEBPAGE
permalink: / String / PERMALINK FOR THE WEBPAGE
tagline: String OPTIONAL GRAVITY FEATURE : TAGLINE FOR THE PAGE
---

---
layout: page
title: "Science"
permalink: /science/
tagline: "Humanity is overrated."
---
```

***

#### Introducing

# ARCHIVE PAGES

#### You can display a list of all the posts corresponding to a particular category on a standalone page using the `ARCHIVE` layout.

- Create a .md file in the root directory.
- Name the file. Preferred name will be the name of the category.
    \*`life.md`
- Write the *Front Matter* and content in the file.

### FORMAT

```
---
layout: archive ARCHIVE PAGE LAYOUT
title: String TITLE OF THE WEBPAGE
permalink: / String / PERMALINK FOR THE WEBPAGE
tagline: String TAGLINE FOR THE PAGE
category: String NAME OF THE CATEGORY OF WHICH THE PAGE WILL SHOW POSTS
---

---
layout: archive
title: "Design"
permalink: "Design"
tagline: "It's all about perception"
category: "design"
---
```

#### DIRECTORY STRUCTURE

```
├── css                                         # => Output of the combined SASS files
│   └── style.scss
├── _includes                                   # => Contains partials that can be used with your layouts
│   ├── footer.html
│   ├── header.html
│   ├── head.html
│   ├── icon-github.html
│   ├── icon-github.svg
│   ├── icon-twitter.html
│   └── icon-twitter.svg
├── _layouts                                    # => Layout related HTML files
│   ├── archive.html
│   ├── default.html
│   ├── page.html
│   └── post.html
├── _posts                                      # => posts, dynamic content. Follow the format: YEAR-MONTH-DAY-title.MARKUP
│   ├── 2016-03-30-design-stories.markdown
│   ├── 2016-03-30-science0.markdown
│   ├── 2016-03-30-science.markdown
│   └── 2016-03-30-welcome-to-jekyll.markdown
└── _sass                                       # => SASS partials for styling
|   ├── _base.scss
|   ├── _layout.scss
|   └── _syntax-highlighting.scss
├── about.md
├── _config.yml                                 # => Configuration options or flags for your site go here
├── design.md
├── download.md
├── feed.xml
├── index.html
├── LICENSE.txt                                 # => Licensing information
├── README.md
└── science.md
```
