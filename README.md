# sample-mkdocs-gh-project

Boilerplate for a Markdown docs project on GitHub Pages.

For step by step instructions see the post [Publish your Markdown docs on GitHub Pages](https://dev.to/ar2pi/publish-your-markdown-docs-on-github-pages-6pe).

For a quick head start:
```sh
# clone and init new repo
export GITHUB_USERNAME="YOUR_GITHUB_USERNAME"
git clone git@github.com:ar2pi/sample-mkdocs-gh-project.git $GITHUB_USERNAME
cd $GITHUB_USERNAME
rm -rvf .git && git init

# replace the "[GITHUB_USERNAME]" string with your GitHub username
LC_ALL=C find ./ -type f -exec sed -i '' -e "s/\[GITHUB_USERNAME\]/$GITHUB_USERNAME/g" {} \;
```
