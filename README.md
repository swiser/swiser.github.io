## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/swiser/swiser.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
```python
def backwards_method(start):
    y_n=0
    #print 'y{:0>2}= {}'.format(start,y_n)
    for x in xrange(start,0,-1):
        y_n=.1*(1.0/x-y_n)
        if x==23:
            print 'Start: {} y{:0>2}= {:.18f}'.format(start,x-1,y_n)
        #print 'y{:0>2}= {}'.format(x-1,y_n)
    #print 'y{:0>2}= {}'.format(0,math.log(11.0/10.0))
```
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
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/swiser/swiser.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
