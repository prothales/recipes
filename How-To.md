
## Markdown

This recipe book is mainly based on Markdown (except for some html pages...).\
There is a great style guide and intro to markdown on [this page](https://google.github.io/styleguide/docguide/style.html).\
Nevertheless all the essentials can be found here.

## Don't repeat yourself

To make sure that all info is up-to-date and that you are not doing double work. instead of repeating yourself link to the place where you already described a subject.
You can check on how to make a link [here](#links).



### Headers

every header is created by starting your sentence with #. \
A single # will create a title. Each time you nest a header deeper you just add a # more.
fo example

```
# title
## header 2
### subtitle
#### even deeper nested subtitle
```

will turn into

--------

# title
## header 2
### subtitle
#### even deeper nested subtitle

--------

### Links

#### external links

You can create a link by simply describing the link in square brackets and then putting the link in between normal brackets.

```
[my links name](www.twikey.com)
```

will turn into

[my links name](www.twikey.com)

#### wiki links

When you want to link to a recipe article please don't use the website links.
this makes it impossible to guarantee all the links keep working.
Instead of using the full link only use it partially, like you would describe the path to a document (which you actually are doing.)

for example

```
[my recipe links name](/branches/development/testing/Test-Guide)
```
Will turn into

[my wiki links name](/branches/development/testing/Test-Guide)

#### links to a single header in a wiki

You only have to add a # and the header name in all lower case to the end of your link. Or only do the header if it is the same wiki article.

for example

```
[my header name](#links-to-a-single-header-in-a-wiki)

or 

[my header name](/branches/development/testing/Test-Guide#test-guide)
```
Will turn into

[my header name](#links-to-a-single-header-in-a-wiki)

or

[my header name](/branches/development/testing/Test-Guide#test-guide)

### collapsable text blocks

If you want to make a text block collapsable you can use this with the following annotation:

```
<details>

my text goes here

</details>
```

If you want to provide a name for the collapsable object you can do the following:

```
<details> <summary> My title </summary>

my text goes here

</details>
```

Respectively they turn into this

<details>

my text goes here

</details>

<details> <summary> My title </summary>

my text goes here

</details>


### adding images

At the bottom right of the article you are writing you can find an upload button.
Using this will upload the image in an upload folder on the wiki and give you a link.
this link can be used exactly the same as creating links to other pages.
The wiki will then render the image for you on the finished page.

### Tables of content

Instead of painstakingly adding every header as a link on the top of your page you can simply add the following at the top.


```
[[_TOC_]]
```


It will automatically add a content table based on all the headers wherever you place it.
Like so:

[[_TOC_]]












