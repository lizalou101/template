# This is a basic project template to speed up boilerplate development

The main focus is to provide code in a ready to use format for learning quickly and efficiently

## Tips and guides for development

1. Always create a branch when adding new code
2. Look at a comparison site for HTML and CSS ideas when attempting to replicate a design

## Notes and Examples of HTML Element use

#### Example of the Title Metadata

```HTML
<!--The title is used on the tab of the browser
and is what someone will see when the go to your page

Place this element in the <head></head> -->

<title>Create your online store today with Shopify</title>
```

#### Adding a container

The `container` HTML element is a `div`

```HTML
<div></div>
```

#### Including a stylesheet in your project

A `link` element is used to include css stylesheets in your HTML file

```HTML
<link rel="stylesheet" href="style.css" />
```

#### Including a script in your project

A `script` element is used to include javascript in your HTML file

```HTML
<script src="index.js"></script>
```

### Including an Image

When including an image on your site here are some options:

#### Using a div container

If you want to use a `div` as a container

- The image will use an `img` element

**NOTE:** adding a `width=""` to the `img` element will assign a fixed width to an image

```HTML
<img src="https://source.unsplash.com/ZRsJmpt9pNI" id="image" width="400">
```

- The caption would youse a `caption` element

```HTML
<caption id="img-caption">Image description</caption>
```

#### using a figure container

If you want to use a `figure` element

```HTML
<figure id="img-div">
```

- The image will use an `img` element (See example above)

- The caption would youse a `figcaption` element

```HTML
<figcaption id="img-caption">Image description</figcaption>
```

#### Adding a header

To create a header us an `h[#}` element

```HTML
<h1>Largest Title (Typically reserved for the title of the site</h1>
<h2>Section Titles</h2>
<h3>Sub Section Titles</h3>
```

#### Adding a link

Links to external sources use an `a` element

```HTML
<a id="" href="https://www.tiktok.com" target="_blank" rel="noopener noreferrer">
```

#### Adding a button with a link

Wrapping a link in a `button` element

```HTML
<button id="">
  <a id="" href="https://www.tiktok.com" target="_blank" rel="noopener noreferrer">
  </a>
</button>
```

#### Adding longer text

To add a paragraph of text or most text in general that requires
more than one line, use a `p` element

```HTML
<p id="">Long paragraph text that spans more than one line
  of text...YAY!
</p>
```

#### Adding short text

To add short text, you can use a `span` element

```HTML
<span id="">Hello there</span>
```

## First Project Challenge

Use https://www.shopify.com/free-trial as an example for the first assignment

### Project Ideas

1. Build a Site for `Rhodes Excavation` which highlights a Backhoe,
   previous jobs, and services offered (Septic System, Foundations, Driveway, Pools),
   and a gallery of the previous work throughout the various phases of the job

2. build a Site for `Horse Clinic` which highlights services offered
   (Horse Therapy, Horse Riding, Care and Upkeep)

### Requirements

1. Add an image across the top and wrapped in a container
2. Add a header beneath the image labeled Services or Products
3. Add a container beneath the header with a class that utilizes a grid setup
4. Within the grid container, add 3 containers, one for each of the grid items
5. Within the grid item:

   1. Add an Image
   2. Add a Header
   3. Add a brief description

6. Add another grid container for an image gallery
7. Within the grid container, add 6 containers, one for each of the grid items
8. Within the grid item
   1. Add an Image
9. Add a button to the bottom of the page which takes the user to another site with more information
