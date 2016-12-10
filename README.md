# play14-website
Main website for #play14 www.play14.org

#### Providing content

You can start providing content by creating a [pull request](https://yangsu.github.io/pull-request-tutorial/) on our [GitHub repository](https://github.com/play14team/play14-website).

Blog posts, Games and Events are all describes in [Markdown](https://daringfireball.net/projects/markdown/) using Jekyll's [YAML Front Matter](https://jekyllrb.com/docs/frontmatter/).  

Directory structure

- Events markdown files should be placed into the `_events` directory. 
  - The file name should respect the template `<yyyy-mm>.md`.
  - Events images should be placed into the `images/events/<event-name>` sub-directory. Their size should be 600x500.
- Games markdown files should be placed into the `_games` directory.
  - The file name should respect the template `<game-name>.md`.
  - Game images should be placed into the `images/games/<game-name>` sub-directory. Their size should be 800x533.
  - Game files should be placed into the `files/<game-name>` sub-directory. 
- Posts markdown files should be placed into the `_posts` directory.
  - The file name should respect the template `<yyyy-mm-dd-post-title>.md`.
  - Post images should be placed into the `images/posts` sub-directory. Their size should be 800x533.

You can find more information on how to write a blog post with Jekyll [here](https://jekyllrb.com/docs/posts/)
