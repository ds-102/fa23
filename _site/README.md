# Data 102 Fall 2023 Website

This [video](https://www.youtube.com/watch?v=azPPK5aOcV0) walks you through how to make changes to the website (just replace all instances of fa19 with fa23 and DS100 with Data 102).

To add Jupyter notebook links to the webpage, use nbgitpuller: https://jupyterhub.github.io/nbgitpuller/link

The following text is taken from the standard GitHub Pages README.


You can use the editor on GitHub to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run Jekyll to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
For more details see GitHub Flavored Markdown.
```

### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your repository settings. The name of this theme is saved in the Jekyll _config.yml configuration file.

### Support or Contact
Having trouble with Pages? Check out our documentation or contact support and we’ll help you sort it out.

### Running Locally
This website is written using Jekyll Bootstrap with some modifications to improve support for github pages.

Install `rvm`: https://rvm.io/ or `rbenv`: https://github.com/rbenv/rbenv. Personally, `rbenv` might work better for me.

Install Ruby 2.2.0:

``rvm install 2.2.0``

Clone this repo:

``git clone https://github.com/ds-102/fa23.git``

In the repo directory, run:

``gem install bundler``
``bundle install``

Finally, serve the project locally with:

``jekyll serve``

This will start the local Jekyll server at http://localhost:4000.
