## How to run locally

1. [Install Zola](https://www.getzola.org/documentation/getting-started/installation/)
2. Clone the repo: `git clone https://github.com/aisnorway/aisnorway.org.git`
3. `cd aisnorway.org && zola serve`

## Writing a blog post

1. Create a new file in `content/blog/`

2. Include the following frontmatter at the top of the file:

```md
+++
title = "Your title"
template = "blog.html"
description = "Your description"
page_template = "blogpage.html"
sort_by = "date"
+++
```

**NB**: Description should be a short summary around 2-3 sentences. This will be what shows up in the post object on the page.

3. Write your content in markdown format underneath. You do not need to write a title, since it will be "Your title" from the frontmatter

4. After you're done, add, commit and push changes to the main branch.

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

## Credits

This theme was partially designed with the inspiration from these fine folks
- [Nathan Randecker](https://github.com/nrandecker/particle)
- [Willian Justen](https://github.com/willianjusten/will-jekyll-template)
- [Vincent Garreau](https://github.com/VincentGarreau/particles.js/)
