1. Download the package or install it with bower

    ```bash
    $ bower install jssocials
    ```
    <div>
        <a href="https://github.com/tabalinas/jssocials/releases/download/v{{ site.version }}/jssocials-{{ site.version }}.zip" class="button success">
            Download jsSocials<br /><small>combined</small>
        </a>
        <a href="https://github.com/tabalinas/jssocials/archive/v{{ site.version }}.zip" class="button">
            Download source<br /><small>.zip file</small>
        </a>
        <a href="https://github.com/tabalinas/jssocials/archive/v{{ site.version }}.tar.gz" class="button">
            Download source<br /><small>.tar.gz file</small>
        </a>
    </div>
2. Add links to `jssocials.css` and chosen theme, e.g. `jssocials-theme-flat.css`
3. Add link to `font-awesome.css` (it's used for social network logos by default, yet you can replace it with image logo or other font if necessary)
4. Add link to `jquery.js` and plugin script `jssocials.min.js`
5. Apply jsSocials to the element on the page `$("#share").jsSocials({ shares: ["twitter"] })`

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="font-awesome.css" />
    <link rel="stylesheet" type="text/css" href="jssocials.css" />
    <link rel="stylesheet" type="text/css" href="jssocials-theme-flat.css" />
</head>
<body>
    <div id="share"></div>

    <script src="jquery.js"></script>
    <script src="jssocials.min.js"></script>
    <script>
        $("#share").jsSocials({
            shares: ["email", "twitter", "facebook", "googleplus", "linkedin", "pinterest", "stumbleupon", "whatsapp"]
        });
    </script>
</body>
</html>
```


##jsSocials CDN

jsSocials is available on [jsdelivr.com](http://www.jsdelivr.com/projects/jquery.jssocials). Use the following CDN links.

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/jquery.jssocials/{{ site.version }}/jssocials.min.js"></script>

<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/jquery.jssocials/{{ site.version }}/jssocials.css" />

<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/jquery.jssocials/{{ site.version }}/jssocials-theme-flat.css" />
<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/jquery.jssocials/{{ site.version }}/jssocials-theme-classic.css" />
<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/jquery.jssocials/{{ site.version }}/jssocials-theme-minima.css" />
<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/jquery.jssocials/{{ site.version }}/jssocials-theme-plain.css" />
```