# Contribution Guidelines

## Overview

Please ensure your pull request adheres to the following guidelines:

* Make sure your submission is not a duplicate.
* Make an individual pull request for each suggestion.
* Adhere to the table formatting (namely keep to the alphabetical order by category, name), which makes for easier reading. I've pasted a snippet of the structure to be completed for each record below.
* The pull request and commit should have a useful title.

Thanks for your suggestions!

Structure of entries:

```html
<table>
    <tr>
        <th>Blog</th>
        <th>Blog Category</th>
        <th>Type</th>
        <th>Blog Link</th>
        <th>Feed Link</th>
    </tr>
    <tr>
        <td>Name of the blog</td>
        <td>If using a specific category/tag feed from the blog, enter this here, else use "All posts"</td>
        <td>Pick one: Analyst, Vendor, Government, Media, Community</td>
        <td>Link to the blog, inc. category/tag filter if applicable. Use markdown format of existing items</td>
        <td>Link to the feed, inc. category/tag filter if applicable. Use markdown format of existing items</td>
    </tr>
</table>
```

To contribute I would recommend the following workflow;

1. make a copy of the [GSheet here](https://docs.google.com/spreadsheets/d/11ebsrFeCaoSup9V3n01tGw4h8vmlVhyQz0kn2EVHM-M/edit?usp=sharing)
2. add your entries
3. select all entries
4. data > sort range > advanced
5. sort column C (a-z), sort column A (a-z)
6. copy table contents
7. [paste into this spreadsheet to HTML convertor, setting output as HTML](https://tableconvert.com/excel-to-html)
8. add the generated HTML to the README.md file in this repo

## Miscellaneous

### Finding feed URLs

Many feeds paths can be guessed when a standard blog framework is used. e.g by appending the following to the URL path;

* `/feed`
* `/rss`

Typically, but not always, feed URLs are also reported in the source code of the blog;

Right-click -> View Page Source -> Ctrl+f `atom` or `rss`

In some cases, blog categories have their own feeds so don't forget to check these if you only want a certain category of posts.

### Dealing with blogs with no feeds

There are a ton of security blogs that don't offer RSS or ATOM feeds. I understand why (namely, concerns over copywrite), but don't necessarily agree with the reasons why.

Why?

There are tons of services that will create feeds from websites, Google; "create rss feed for a website".

For example; https://rss.app/, https://fetchrss.com/, are just a few examples.

I can't recommend any, but on cursory testing they appear to pretty good at creating live feeds for blogs and Twitter feeds.
