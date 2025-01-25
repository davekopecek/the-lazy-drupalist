# The Lazy Drupalist

A dumping ground for my thoughts on Drupal and ever-so-occasional attempts at improving the lives of folks who wade in the same waters. Created by me, [Dave Kopecek](https://www.davekopecek.com/).

## ⚠️ Important Technical Note

**TEMPORARY FIX IN PLACE**: We're currently suppressing Sass deprecation warnings that stem from using the legacy `@import` syntax. This will need to be addressed in the future as:

1. `@import` is being deprecated in Sass
2. The jekyll-theme-so-simple theme heavily relies on `@import`
3. Recent updates to Ruby, Jekyll, and jekyll-sass-converter have made this more urgent

**TODO: Major refactor needed**
- Theme needs to be forked and updated to use `@use`/`@forward`
- All Sass files need to be modernized
- Variables need to be properly scoped
- Module system needs to be implemented correctly

## About

This blog documents adventures and experiences working with Drupal, sharing tips, tricks, and solutions that might help other Drupal developers. The blog is implemented using Jekyll with the So Simple theme.

## How this thing works

I work on Windows, because I'm too cool for Linux and too cheap for Mac. 

### Prerequisites
- Windows Subsystem for Linux (WSL) with Ubuntu
- Ruby installed via WSL
- Jekyll and Bundler gems

### Local Setup on WSL

1. Start WSL and navigate to the project directory:
2. Install dependencies and run the Jekyll server:
``` bash
bundle install
bundle exec jekyll serve
```

To build the site with optimized images:
``` bash
npm run build
```

This command will:
1. Optimize any new images in the `images/` directory (backing up originals to `images/originals/`)
2. Build the Jekyll site

For development without image optimization:

The site will be available at `http://localhost:4000`

### Creating a New Post

1. Create a new markdown file in `_posts/blog` with the filename format: `YYYY-MM-DD-title-of-post.md`

2. Add the front matter at the top of the file:

## Theme Documentation

Information about the So Simple theme can be found in [THEME.md](THEME.md).

## Links

- [Live Blog](https://github.com/davekopecek/the-lazy-drupalist)
- [Source Code](https://github.com/davekopecek/the-lazy-drupalist)
- [Author's Website](https://www.davekopecek.com/)

