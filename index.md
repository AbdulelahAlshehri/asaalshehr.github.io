## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/asaalshehr/asaalshehr.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<div class="sharebuttons">
  <hr />
  <ul>
    <li>
      <p class="sharetitle"> Share this: </p>
    </li>
    <li class="reddit">
      <a href="http://www.reddit.com/submit?url={{ page.url | replace:'index.html','' | prepend: site.baseurl | prepend: site.url | uri_escape}}&title={{ page.title | default:"" | uri_escape }}" target="_blank">
        {% include social/share-icon-reddit.svg %}
      </a>
    </li>
    <li class="hn">
      <a href="http://news.ycombinator.com/submitlink?u={{ page.url | replace:'index.html','' | prepend: site.baseurl | prepend: site.url | uri_escape}}&t={{ page.title | default:"" | uri_escape}}" target="_blank">
        {% include social/share-icon-hn.svg %}
      </a>
    </li>
    <li class="twitter">
      <a href="https://twitter.com/intent/tweet?via=USERNAME&url={{ page.url | replace:'index.html','' | prepend: site.baseurl | prepend: site.url | uri_escape}}&text={{ page.title | default:"" | uri_escape}}" target="_blank">
        {% include social/share-icon-twitter.svg %}
      </a>
    </li>
    <li class="linkedin">
      <a href="https://www.linkedin.com/shareArticle?mini=true&url={{ page.url | replace:'index.html','' | prepend: site.baseurl | prepend: site.url | uri_escape}}&title={{ page.title | default:"" | uri_escape}}" target="_blank">
        {% include social/share-icon-linkedin.svg %}
      </a>
    </li>
  </ul>
</div>

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
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/asaalshehr/asaalshehr.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
