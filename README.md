# ROH Digital blog

A blog about digital projects at the Royal Opera House, administered as a [Jekyll](https://jekyllrb.com/) site hosted in [GitHub Pages](https://pages.github.com/).

## Site structure

- `_config.yml` is the Jekyll configuration.
- `index.md` is the contents of the site's homepage.
- Files in `_posts/` are listed on the homepage from newest to oldest.
- Files in `_images/` can be used as images in posts.

## Publishing notes

You can use the [editor on GitHub](https://github.com/royaloperahouse/royaloperahouse.github.io/edit/main/README.md) to maintain and preview the content of the site in [Markdown](https://guides.github.com/features/mastering-markdown/) files.

When creating a new post,

- The post's filename needs to start with a date in the YYYY-MM-DD format, e.g. `2021-04-21-title-of-post.md`
- The post title should be wrapped in quotes, for example: `title: "This week's sprint"`

The [live site](https://royaloperahouse.github.io/) is automatically updated when you make changes in GitHub.

### Adding images

1. In GitHub, upload the image file in the `_images/` folder.
2. Reference the image with the correct path and file name from your post: `![Image alt text](/_images/my-file-name.png)`.
