# my-page
Build and deploy a static business website in 15 minutes
You need to build a simple static website? The best tool I’ve seen so far is Hugo, a static website builder written in Go.
Start building the page

    Install Hugo, create a project directory and run the following in your terminal:

hugo new site my-page

2. Change to the directory and initialize a git repo:

cd my-page && git init

3. Install a theme (hugo-fresh business theme)

git submodule add https://github.com/StefMa/hugo-fresh.git themes/hugo-fresh && curl -O https://raw.githubusercontent.com/StefMa/hugo-fresh/master/exampleSite/config.yaml && rm config.toml

4. Run your website locally and browse it at http://localhost:1313

hugo server

Now you can see your website
