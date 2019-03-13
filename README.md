<div align="center">

# CSS GRID SET

![Language](https://img.shields.io/github/languages/top/prod3v3loper/css-grid.svg?style=flat "Language")
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8b3e23d14b88426d83660ad87bca129d)](https://www.codacy.com/app/prod3v3loper/css-grid?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=prod3v3loper/css-grid&amp;utm_campaign=Badge_Grade)
![Languages](https://img.shields.io/github/languages/count/prod3v3loper/css-grid.svg?style=flat "Languages")
![Size](https://img.shields.io/github/size/prod3v3loper/css-grid/grid.css.svg?style=flat "Size")
![Code size](https://img.shields.io/github/languages/code-size/prod3v3loper/css-grid.svg?style=flat "Code size")
![Repo size](https://img.shields.io/github/repo-size/prod3v3loper/css-grid.svg?style=flat "Repo size")
![License](https://img.shields.io/github/license/prod3v3loper/css-grid.svg?style=flat "License")
[![Website](https://img.shields.io/website-up-down-green-red/https/www.tnado.com/open-source-projects-by-prod3v3loper.svg?style=flat "Website")](https://www.tnado.com/open-source-projects-by-prod3v3loper/ "Website")

This is a css repo with calculated grids

> A curated list of awesome CSS grids

[Tests Preview](test/img/tests.png)

### This repository has some grids for you:

</div>

* [l-cell](partials/_cell.css) 13 cell
* [l-col](partials/_col.css) 24 col
* [l-grid](partials/_grid.css) 12 grid
* [l-row](partials/_row.css) 16 row

# Usage

### General Usage

In general you should include the file `grid.css` in `build` into your 
project css or less/sass folder structur and use the grid, col, cell or row as suggested in the docs for each grid, col, cell or row.

#### Example

###### @import

```less
@import 'your-css-folder/grid.css';
```
###### @link

```html
<link rel="stylesheet" href="your-css-folder/grid.css">
```

###### @use

12 grid
```html
<div class="l-grid--6">
    <p>Content</p>
</div>
<div class="l-grid--6">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

13 cell
```html
<div class="l-cell--6">
    <p>Content</p>
</div>
<div class="l-cell--7">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

16 row
```html
<div class="l-row--8">
    <p>Content</p>
</div>
<div class="l-row--8">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

24 col
```html
<div class="l-col--12">
    <p>Content</p>
</div>
<div class="l-col--12">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

<div align="center">

# Contribute

Please [file an issue](https://github.com/Samettarim/less-mixins/issues) if you
think something could be improved. Please submit Pull Requests when ever
possible.

# Built with

[NetBeans](https://netbeans.org/) - NetBeans editor for error-free code

# Authors

**Samet Tarim** - *All works*

# License

[GNU](https://github.com/prod3v3loper/css-grid/blob/master/LICENSE) - [prod3v3loper](https://www.tnado.com/author/prod3v3loper/)

</div>