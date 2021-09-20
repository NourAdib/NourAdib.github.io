# NourAdib.github.io
This is my lab 1 submission for the web programming course.
***
### This website is composed of 3 sections:
1. [The Home section](https://nouradib.github.io/).
2. [The About section](https://nouradib.github.io/about/).
3. [The Blog section](https://nouradib.github.io/blog/).
***
### How this website was created:
#### The HTML:
1. The HTML was used to structure the content of the pages. 
2. The [layouts folder](https://github.com/NourAdib/NourAdib.github.io/tree/main/_layouts) contains the HTML templates used for the blog posts and the rest of the pages.
3. Each of the section in the website [mentioned above](https://github.com/NourAdib/NourAdib.github.io/blob/main/README.md#this-website-is-composed-of-3-sections) has an index.html file dedicated to it, these files are based on the [default.html](https://github.com/NourAdib/NourAdib.github.io/blob/main/_layouts/default.html) template.
4. The blog posts are based on the [post.html](https://github.com/NourAdib/NourAdib.github.io/blob/main/_layouts/post.html).

#### The CSS:
The website's pages are based on the [default.html](https://github.com/NourAdib/NourAdib.github.io/blob/main/_layouts/default.html) template and therefore only needed one [CSS file](https://github.com/NourAdib/NourAdib.github.io/tree/main/css) to style it.

#### Jekyll:
1. Jekyll was used to handle and generate the HTML files. This was done by leaving Jekyll liquid tags in the HTML template code and then specifying the content that should replace them when creating the index.html files as in the [About](https://nouradib.github.io/about/) and [Blog](https://nouradib.github.io/blog/) sections.
2. Jekyll also usese the [congif.yml](https://github.com/NourAdib/NourAdib.github.io/blob/main/_config.yml) file to generate the permalinks for the blog posts.
3. Jekyll also stores the files for the blog posts in the [posts](https://github.com/NourAdib/NourAdib.github.io/tree/main/_posts) folder.
