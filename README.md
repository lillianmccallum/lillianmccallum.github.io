This repo contains files for a website. 

Website URL is `https://<github username>.github.io/` where `<github username>` is replaced with your github username

Set up:

1. Install Ruby
- Download and install Ruby from [Ruby](https://www.ruby-lang.org/en/downloads/).
- During the installation, ensure you check the option to add Ruby to your system's PATH.
2. Install Jekyll and Bundler
- Open a Command Prompt or PowerShell window.
- Install Bundler and Jekyll using the following commands:
```
gem install jekyll bundler
```
- If you get an error, try:
```
ridk install
```
3. Navigate to Your Jekyll Site Directory
- In the Command Prompt or PowerShell, navigate to the root directory of your Jekyll project (where your Gemfile is located):
```
cd path\to\your\jekyll-site
```
- Replace path\to\your\jekyll-site with the actual path to your Jekyll project.

4. Install the Dependencies
- Once in the project directory, run:
```
bundle install
```
- This will install the necessary dependencies as specified in your Gemfile.

5. Serve the Jekyll Site Locally
- Start the Jekyll server with:
```
bundle exec jekyll serve
```
- This will build the site and start a local server, which will be accessible at http://localhost:4000.
- This probably requires making the folder into a git repo (see [the docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)) and make sure to name your repo `<github username>.github.io` when pushing to github

6. View Your Site
- Open your web browser and go to http://localhost:4000 to view your site. You can now edit your files and see the changes live.
7. Stop the Server
- When you're done, you can stop the server by pressing CTRL + C in the Command Prompt or PowerShell.
8. Push to github and wait for the Site to Go Live
- In the "Pages" settings of your repository, ensure that the "Enforce HTTPS" option is enabled. This will ensure your site is served securely over HTTPS.
- It may take a few minutes for GitHub Pages to build and deploy your site. Once done, you can access your site at `https://<yourusername>.github.io.`
- Clear your browser cache or use a private/incognito window to ensure you see the latest version of your site.