![# Raphaels Madonnas logo][logo]
### Jekyll Start Command
bundle exec jekyll serve

### Created Using Jekyll
[Jekyll] is a static site generator, with great blogging/posting capabilities.

### Responsive Comic Strip Layout
Uses [flex-box] to create a responsive comic strip layout. See [web-comic.css] on Github for more details.

### Archive
Used [this] article to create my Archive page without using any plugins.
Jekyll has some cool things you can do with categories/tags.

### Jekyll Install Notes 
When attempting to install Jekyll on High Sierra, you’ll receive an error that you don’t have permissions to a library. The issues that you need to manage Ruby. The first step is to groom our Ruby environment. To do this, we need to utilize Homebrew

1. Install Homebrew
    * Homebrew is a package manager
2. Then install rbenv
    * rbenv helps to groom your app’s Ruby environment
    * Follow all the steps!
3. Install Ruby (directions on rebenv site from above)
4. Install Ruby gems
    * $ gem install bundler
5. Install the bundler 
    * $ install bundler (bundle install)
    * The previous step installed the installer, but didn’t actually run the bundler
6. Install Jekyll bundler
    * $ gem install Jekyll bundler
7. Make a new Jekyll site
    * Jekyll new my-awesome-site
8. CD to that location
    * Cd my-awesome-site
9. Run the serve command
    * $ bundle exec Jekyll serve
    * The first time, have to do bundle exec Jekyll serve. After this, should be able to do “Jekyll serve” if don’t want to run everything
    
### GitHub Pages
[GitHub Pages] allows you to host directly from your GitHub repo. When using GitHub pages, site is https://leeessner.github.io/RaphaelsMadonnas/. When push to master, site automatically updates. A custom domain can be added.

[logo]:https://leeessner.github.io/RaphaelsMadonnas/images/img_frame/1502_Solly-Madonna-frame.png
[flex-box]:https://css-tricks.com/snippets/css/a-guide-to-flexbox/
[this]:https://codinfox.github.io/dev/2015/03/06/use-tags-and-categories-in-your-jekyll-based-github-pages/
[Jekyll]:http://jekyllrb.com
[web-comic.css]:https://github.com/karlyanelson/web-comic.css
[GitHub Pages]:https://pages.github.com/
