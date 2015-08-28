 jekyll-theme-gh-slate

GitHub Slate theme ported from GitHub Pages theme browser for custom Jekyll skinning

# Author

Originally by: ...
Ported by Jonathan Tsai <akajontsai-devel@yahoo.com>
Modified by Efreak <efreak@users.noreply.github.com>

After the theme is set up, one easy command to package it for publishing!

    $ rake theme:package name="THEME-NAME"

# Configuration

    $ rake theme:install git="https://github.com/Efreak/jekyll-theme-gh-slate"
    ...
    => Want to switch themes now? [y/n] y

Now edit _config.yml with the following:

```
title : jekyll-theme-gh-slate
tagline: GitHub Slate theme ported from GitHub Pages theme browser for custom Jekyll skinning
author :
  name : Name Lastname
  email : blah@email.test
  twitter : username
  github : username
  github_project : jekyll-theme-gh-slate
```

`github_project` is the part of the url that comes after your username.
