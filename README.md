# blendedshire.com

## Setup
1. Clone the repo `git clone git@github.com:blendedshire/blendedshire.github.io.git`
2. `cd blendedshire.github.io`
3. `bundle install`

## Writing new posts
1. Create a new branch when you want to make changes. `git checkout -b my-branch-name`
2. Create a file in `_posts/` with a date for publishing `2017-10-27-sourdough-starter.md`
3. Include YAML front matter using the `_drafts/2014-11-30-mediator_features.markdown` as example
4. Follow writing posts like [this](https://jekyllrb.com/docs/posts/)
5. Use `jekyll serve --watch` to see site locally at `localhost:4000`
6. You can commit as you go or just commit when the post is ready
7. Push your changes to the server `git push`
8. Create a Pull Request on [github](http://github.com/blendedshire/blendedshire.github.io)
9. This gives you a place to read over them and to have someone else proofread and make comments
10. Repeat 6 & 7 as needed
11. Merge pull request when post is ready this will update site automatically
