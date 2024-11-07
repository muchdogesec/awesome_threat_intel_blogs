# Contribution Guidelines

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
        <th>Feed Type</th>
        <th>Last checked</th>
    </tr>
    <tr>
        <td>Name of the blog</td>
        <td>If using a specific category/tag feed from the blog, enter this here, else use ALL</td>
        <td>Pick one: Analyst, Vendor, Government, Media, Community</td>
        <td>Link to the actual blog, inc. category/tag filter if applicable</td>
        <td>Link to the actual feed, inc. category/tag filter if applicable</td>
        <td>The type of feed, either: ATOM or RSS</td>
        <td>The date you added or modified this entry</td>
    </tr>
</table>
```

To contribute I would recommend the following workflow;

1. make a copy of the [GSheet here](https://docs.google.com/spreadsheets/d/11ebsrFeCaoSup9V3n01tGw4h8vmlVhyQz0kn2EVHM-M/edit?usp=sharing)
2. add your entries
3. format > sort range > advanced
4. sort column C (a-z), sort column A (a-z)
5. copy table contents
6. [paste into this spreadsheet to HTML convertor, setting output as HTML](https://tableconvert.com/excel-to-html)
7. add the generated HTML to the README.md file in this repo