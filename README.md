HackRolla Website/Blog
======================
- Hosted with [Github Pages](https://pages.github.com/)
- Built with [Jekyll](http://jekyllrb.com/)
- Using a modified version of [minimal-block](https://github.com/drvy/minimal-block) Jekyll theme

Updating Directions
===================
- `git clone git@github.com:HackRolla/hackrolla.github.io.git`
- Make new posts in the `_posts` directory (follow the layout of what's already in there)
- Any images you need should be put in the `imgs/` directory
- `git add` the files you edited or created
- `git commit` and write a somewhat-useful commit message
- `git push` and GitHub will automatically rebuild the website with your changes

Notes:
- Don't commit anything from the `_site` directory. That's auto-generated. 
- If you want to check the website locally before you commit/push:
	- Edit `_config.yml`, comment out the `url: http://hackrolla.github.io` line and uncomment the `url: http://localhost:4000`	line
	- If you haven't already, install jekyll and bundler (the github pages help tells you how to do this far better than I can)
	- `bundler exec jekyll serve` will start a local webserver where you can see your changes
