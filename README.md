![alt tag](https://farm2.staticflickr.com/1593/25549169123_cfb392bfe9.jpg)

---


If there's any issue you are facing in setting up this theme I'm there for you. Just create an issue in this repository (http://github.com/hemangsk/Gravity), (https://help.github.com/articles/creating-an-issue/) and I'll get back to you asap.


![alt-tag](https://farm8.staticflickr.com/7295/26900743846_10e9a0ba71_o.png)
![alt-tag](https://farm8.staticflickr.com/7675/26840339222_b078607576_o.png)
![alt-tag](https://farm2.staticflickr.com/1592/26151881165_3f351e5fd1.jpg)
___

# POSTING
- Create a .markdown file inside `_posts` folder.
- Name the file according to the format YY-MM-DD-[short name for your post].
- `2016-03-30-i-love-design.markdown`
- Write the _Front Matter_ and content in the file.

## FORMAT
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
___

# CREATE PAGES
- Create a .md file in the root directory.
- Name the file with the desired page link name.
`about.md`
`design.md`
- Write the _Front Matter_ and content in the file.

##FORMAT
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
___
# INTRODUCING ARCHIVE PAGES
#### You can display a list of all the posts corresponding to a particular category on a standalone page using the `ARCHIVE` layout.

- Create a .md file in the root directory.
- Name the file. Preferred name will be the name of the category.
	*`life.md`
- Write the _Front Matter_ and content in the file.

##FORMAT
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


### Directory structure
```
├── css 									    # => Output of the combined SASS files
│   └── style.scss
├── _includes									# => Contains partials that can be used with your layouts
│   ├── footer.html
│   ├── header.html
│   ├── head.html
│   ├── icon-github.html
│   ├── icon-github.svg
│   ├── icon-twitter.html
│   └── icon-twitter.svg
├── _layouts									# => Layout related HTML files
│   ├── archive.html
│   ├── default.html
│   ├── page.html
│   └── post.html
├── _posts										# => posts, dynamic content. Follow the format: YEAR-MONTH-DAY-title.MARKUP	
│   ├── 2016-03-30-design-stories.markdown
│   ├── 2016-03-30-science0.markdown
│   ├── 2016-03-30-science.markdown
│   └── 2016-03-30-welcome-to-jekyll.markdown
└── _sass										# => SASS partials for styling
|   ├── _base.scss
|   ├── _layout.scss
|   └── _syntax-highlighting.scss
├── about.md
├── _config.yml 								# => Configuration options or flags for your site go here
├── design.md
├── download.md
├── feed.xml
├── index.html
├── LICENSE.txt									# => Licensing information
├── README.md
└── science.md
```
