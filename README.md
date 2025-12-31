Website based on Hydra Jekyll theme `https://jekyllthemes.io/theme/hydra-jekyll-theme`

To run locally, follow the [Instructions](https://jekyllrb.com/docs/) specified in the Jekyll documentation. When you have installed all prerequisites, run:
```sh
gem install jekyll bundler
```

Enter the folder:
```sh
cd BAMeScience.github.io/
```

and install the dependencies:
```sh
bundle install
```

Then, execute:
```sh
bundle exec jekyll serve
```

to run the local server. The terminal will show the localhost where the web is deployed:
```sh
Configuration file: /home/<user-directory>/BAMeScience.github.io/_config.yml
            Source: /home/<user-directory>/BAMeScience.github.io
       Destination: /home/<user-directory>/BAMeScience.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
       Jekyll Feed: Generating feed for posts
                    done in 0.203 seconds.
 Auto-regeneration: enabled for '/home/<user-directory>/BAMeScience.github.io'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop
```

Click on the server address to visualize the website. You can add the option `--livereload` to serve to automatically refresh the page with each change you make to the source files:
```sh
bundle exec jekyll serve --livereload
```
